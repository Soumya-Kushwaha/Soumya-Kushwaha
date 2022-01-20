### Hi there! 👋

- 🌱 I’m currently learning DSA
- 🔭 I’m currently solving problems on LeetCode and GeeksforGeeks
- 🤔 I’m looking for help with development.
- 💬 Ask me about C++, mysql.
- 📫 How to reach me: https://www.linkedin.com/in/kushwaha-soumya
- ⚡ Fun fact: We can talk about astrophysics all day!

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=soumya-kushwaha)](https://github.com/soumya-kushwaha/github-readme-stats)

START_SECTION:activity
name: Update README

on:
  schedule:
    - cron: '*/30 * * * *'
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    name: Update this repo's README with recent activity

    steps:
      - uses: actions/checkout@v2
      - uses: soumya-kushwaha/github-activity-readme@master
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

<!--
**Soumya-Kushwaha/Soumya-Kushwaha** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:
-->
