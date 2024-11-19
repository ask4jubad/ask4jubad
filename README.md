- 👋 Hi, I’m @ask4jubad
- 👀 I’m interested in general engineering and IT 
- 🌱 I’m currently learning compiler construction, and actually using java😉. I am also currently exploring testing as a scientific exercise.
- 💞️ I’m looking to collaborate on SDGs, startups, digital solutions, teaching and having fun.
- 📫 How to reach me skype/facebook/linkedin/twitter/instagram: ask4jubad

<!---
ask4jubad/ask4jubad is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

[![Ask4jubad's GitHub stats](https://github-readme-stats.vercel.app/api?username=ask4jubad&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage&show_icons=true&theme=radical)](https://github.com/ask4jubad/github-readme-stats)


![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ask4jubad&hide_progress=false)


file1 = open('name.txt')
file2 = open('name2.txt', 'w')
reader = file1.readlines()
gather = []
reader.sort(reverse=True)
for i in reader:
    p = list(i)
    p.sort(reverse=True)
    rev2 = ''
    for j in p:
        if j != '\n':
            rev2 += j

    file2.write(rev2)
    file2.write('\n')
