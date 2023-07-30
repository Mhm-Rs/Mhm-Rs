![Header](./github-header-image.png)


I'm a junior software engineer who likes to try new techs through projects.

> Currently working on : **Movie Review FullStack App** with : 
> - Spring
> - MongoDB
> - ReactJS

Find me here :
- [<img height="32" width="32" src="https://cdn.simpleicons.org/linkedin/#0A66C2" />](https://www.linkedin.com/in/rais-mohaman/)
- [<img height="32" width="32" src="https://cdn.simpleicons.org/youtube/#FF0000" />](https://www.youtube.com/@raismohaman6151)

<!--START_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}
<!--END_SECTION:waka-->


<!--
**Mhm-Rs/Mhm-Rs** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
