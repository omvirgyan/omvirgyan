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

> 📌 **Problem:** [Unique Paths](https://leetcode.com/problems/unique-paths/)  
> 🗓️ **Date:** 2025-07-21  
> 🧑‍💻 **Language:** Java  

#### 📄 Solution submitted by me

```java

class Solution {
    public int pathCount(int i, int j, int m, int n,int[][] dp) {
        if (i == m - 1 && j == n - 1)
            return 1;
        if (i >= m || j >= n)
            return 0;
        if(dp[i][j]!=-1) return dp[i][j];
        int right = pathCount(i, j + 1, m, n,dp);
        int down = pathCount(i + 1, j, m, n,dp);
        dp[i][j]=right + down;
         return dp[i][j];
    }

    public int uniquePaths(int m, int n) {
        int[][] dp = new int[m + 1][n + 1];
        for (int[] row : dp) {
            Arrays.fill(row, -1);
        }
        return pathCount(0, 0, m, n,dp);
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
