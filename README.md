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

> 📌 **Problem:** [House Robber](https://leetcode.com/problems/house-robber/)  
> 🗓️ **Date:** 2025-07-18  
> 🧑‍💻 **Language:** Java  

#### 📄 Solution submitted by me

```java

class Solution {
    public int amountRob(int[] arr,int idx,int[] dp){
        if(idx>=arr.length) return 0;
        if(dp[idx]!=-1)return dp[idx];
        int take=arr[idx]+ amountRob(arr,idx+2,dp);
        int skip=amountRob(arr,idx+1,dp);
        
        return dp[idx]=Math.max(take,skip);
    }
    public int rob(int[] nums) {
       int [] dp=new int[nums.length];
       Arrays.fill(dp,-1);
       return amountRob(nums,0,dp);
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
