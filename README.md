# Yield Curve Modeling  
## **Government Bond Yield Curve Modeling — CBK, Kenya**

This project focuses on modeling the yield curve for Kenyan government securities (CBK T-Bills).  
The task involves gathering yield data, applying modeling techniques (Nelson–Siegel & Cubic Spline), evaluating fit performance, and interpreting results.

---

## **Tasks Covered**

### **Task 2 — Yield Curve Modeling (CBK, Kenya)**

**(a)** Select government securities from a chosen country  
*Kenya — Central Bank Treasury Bills (CBK T-Bills)*

**(b)** Use short to longer maturities  
*91-day, 182-day, 364-day (or extend using longer bonds if available)*

**(c)** Fit a **Nelson–Siegel** model  
- Estimate parameters:  
  - **Alpha1 = β₀**  
  - **Alpha2 = β₁**  
  - **Alpha3 = β₂**  
  - **Alpha4 = λ**  
- Explore the shape of the curve based on parameter signs  
- Compute model-predicted yields

**(d)** Fit a **Cubic Spline** model  
- Fit a smooth spline curve through yields  
- Compare flexibility vs NS model  
- Visualize local curvature

**(e)** Compare model fits  
- Use **RMSE (Root Mean Squared Error)**  
- Highlight which model better captures yield dynamics  
- Discuss overfitting vs smoothness

**(f)** Report parameter levels  
- Interpret β₀ (long-term level)  
- Interpret β₁ (slope)  
- Interpret β₂ (curvature)  
- Interpret λ (decay rate)  

**(g)** Address whether smoothing (Nelson–Siegel) is unethical  
- Explain advantages of smoothing  
- Discuss transparency, interpretation, and risk implications  
- Clarify why smoothing is acceptable if assumptions are well-stated  

---

## **Modeling Summary**

### Nelson–Siegel Model
- Captures overall *shape* of yield curve  
- Uses level, slope, and curvature factors  
- Provides smooth, interpretable curves  
- Good for macro modeling and forecasting

### Cubic Spline Model
- Highly flexible  
- Captures local variations  
- Better for very detailed yield shapes  
- Risk of overfitting due to too much flexibility

---

## **Key Deliverables**
- Cleaned security yield dataset (Kenya T-Bills)  
- Nelson–Siegel yield curve  
- Cubic Spline yield curve  
- RMSE comparison  
- Parameter table  
- Interpretation of yield curve dynamics  
- Ethical discussion of curve smoothing  

---

## **Tools & Libraries Used**

- Python  
- pandas  
- numpy  
- matplotlib  
- statsmodels / custom optimization  
- scipy.interpolate (for splines)

---

