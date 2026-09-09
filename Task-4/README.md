# Task-4
# AI/ML Internship - Task 4: Feature Encoding & Scaling

## Dataset
- **Adult Income Dataset** (UCI): Predict >$50K income from census data.[web:2]
- Downloaded: https://archive.ics.uci.edu/static/public/2/data.csv

## Steps Followed (per Task Hints)
1. **Identified Features**: Numerical (6), Ordinal Cat (1), Nominal Cat (7).[file:1]
2. **Encoding**:
   - Label Encoding: education (ordinal).
   - One-Hot: workclass, marital-status, etc. (nominal).
3. **Scaling**: StandardScaler on numerical → mean=0, std=1.
4. **Handled Missing**: Mode/median imputation + drop NaN.
5. **Visualized**: Before/after histograms (see images).
6. **Saved**: `adult_processed.csv`

## Key Results
## Visualizations
![Before After Scaling](before_after_scaling.png)  
![Dataset Describe Post-Processing](describe_post.png)  <!-- Add your screenshot -->
## Tools Used
- Python, Pandas, Scikit-learn, Matplotlib, Seaborn (free, no paid tools).[file:1]
- Google Colab
## Explanations
- **Scaling Impact**: Prevents dominance by high-range features (e.g., fnlwgt) in ML algos like SVM/NN.[web:11][file:1]
- **Encoding Choice**: Avoids ordinal bias in nominal data.



**Completed: January 21, 2026**  
**Student: Asim927** | Hyderabad, Telangana
