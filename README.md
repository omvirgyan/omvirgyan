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

> 📌 **Problem:** [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/)  
> 🗓️ **Date:** 2025-08-06  
> 🧑‍💻 **Language:** Java  

#### 📄 Solution submitted by me

```java

class Solution {
    public int lengthOfLIS(int[] nums) {
        if (nums.length == 0) return 0;

        int[] dp = new int[nums.length];
        dp[0] = 1;
        int ans = 1;

        for (int i = 1; i < dp.length; i++) {
            int max = 0;
            for (int j = 0; j < i; j++) {
                if (nums[i] > nums[j]) { 
                    max = Math.max(max, dp[j]);
                }
            }
            dp[i] = max + 1;
            ans = Math.max(ans, dp[i]);
        }

        return ans;
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
