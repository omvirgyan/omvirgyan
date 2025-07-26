<h1 align="center">Hi 👋, I'm Omvir Gyan</h1>
<h3 align="center">Data Analyst | Full Stack Developer | CSE'26</h3>

---

## 📌 About Me

- 🎓 B.Tech in Computer Science (GLA University)
- 💡 Passionate about **Data Analytics**, **SQL + Python**, and **MERN stack**
- 💼 Actively building:  
  - ✅ Employee Management System  
  - ✅ Ecommerce Data Analytics  
  - ✅ Anti-Procrastination Chrome Extension

---

## 🚀 Skills

- **Languages**: Java, Python, JavaScript, SQL  
- **Libraries**: Pandas, NumPy, Plotly, Seaborn  
- **Web**: Node.js, Express, MongoDB, React, Tailwind CSS  
- **Tools**: VS Code, MySQL, MongoDB Compass, Power BI  
- **Other**: Git, GitHub Actions, Selenium Automation

---

## 📈 LeetCode Stats

<p align="center">
  <a href="https://leetcode.com/u/Omvirgyan/">
    <img src="https://leetcard.jacoblin.cool/Omvirgyan?theme=dark&font=Baloo&ext=heatmap" alt="LeetCode Profile Card" />
  </a>
</p>

---

## 🧠 Latest LeetCode Submission

<!-- LEETCODE-LAST-SUBMISSION:START -->
### 

> 📌 **Problem:** [Count Square Submatrices with All Ones](https://leetcode.com/problems/count-square-submatrices-with-all-ones/)  
> 🗓️ **Date:** 2025-07-26  
> 🧑‍💻 **Language:** Java  

#### 📄 Solution submitted by me

```java

class Solution {
    public int countSquares(int[][] matrix) {
         int m = matrix.length;
        int n = matrix[0].length;
        int count=0;
        for(int i=0;i<m;i++){
            for(int j=0;j<n;j++){
              if(matrix[i][j]==0) continue;
              if(i>0 && j>0){
                matrix[i][j] +=min(matrix[i-1][j],matrix[i][j-1],matrix[i-1][j-1]);
              }
              count +=matrix[i][j];
            }
        }
        return count;
    }
    public static int  min(int a,int b,int c){
        return Math.min(a,Math.min(b,c));
    }
}
```
<!-- LEETCODE-LAST-SUBMISSION:END -->

---

## 🔗 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin&logoColor=white)](https://linkedin.com/in/omvirgyan)  
📧 omvirgyan3@gmail.com

---

## 👁️ Visitor Count

![Visitor Badge](https://komarev.com/ghpvc/?username=omvirgyan&style=flat-square&color=blue)
