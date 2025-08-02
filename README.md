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

> 📌 **Problem:** [House Robber II](https://leetcode.com/problems/house-robber-ii/)  
> 🗓️ **Date:** 2025-08-02  
> 🧑‍💻 **Language:** Java  

#### 📄 Solution submitted by me

```java

class Solution {
    public int amountRob(int[] arr, int start, int end, int[] dp) {
        if(start > end) return 0;
        if(dp[start] != -1) return dp[start];
        int take = arr[start] + amountRob(arr, start + 2, end, dp);
        int skip = amountRob(arr, start + 1, end, dp);
        return dp[start] = Math.max(take, skip);
    }
    public int rob(int[] nums) {
        int n = nums.length;
        if(n == 1) return nums[0];
        int[] dp1 = new int[n];
        int[] dp2 = new int[n];
        Arrays.fill(dp1, -1);
        Arrays.fill(dp2, -1);
        int case1 = amountRob(nums, 0, n - 2, dp1); 
        int case2 = amountRob(nums, 1, n - 1, dp2);  
        return Math.max(case1, case2);
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
