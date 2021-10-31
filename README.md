###สวัสดีจ้า 👋name: GitHub Actions Demo

on: [push]

jobs:

  Explore-GitHub-Actions:

    runs-on: ubuntu-latest

    steps:

      - run: echo "🎉 The job was automatically triggered by a ${{ github.event_name }} event."

      - run: echo "🐧 This job is now running on a ${{ runner.os }} server hosted by GitHub!"

      - run: echo "🔎 The name of your branch is ${{ github.ref }} and your repository is ${{ github.repository }}."

      - name: Check out repository code

        uses: actions/checkout@v2

      - run: echo "💡 The ${{ github.repository }} repository has been cloned to the runner."

      - run: echo "🖥️ The workflow is now ready to test your code on the runner."

      - name: List files in the repository

        run: |

          ls ${{ github.workspace }}

      - run: echo "🍏 This job's status is ${{ job.status }}."



<!--
**prdarm/Prdarm** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
