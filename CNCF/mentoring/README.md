# CNCF Mentoring helper prompts

## pull info from a project_ideas file and create a `.csv`

Model: ChatGPT o1  
Sample: <https://chatgpt.com/share/679d4980-51e0-8004-91f6-4d9ccebe181a>

<blockquote>
Could you help me move information in this project ideas page (shared below) into a google sheet with the following headings:

~~~
```
PROJECT
LFX URL
Upstream Issue
project made mentee selection
mentor count in LFX
Mentor 1
Mentor 1 GitHub
Mentor 1 email address
Mentor 2
Mentor 2 GitHub
Mentor 2 email address
Mentor 3
Mentor 3 GitHub
Mentor 3 email address
Mentor 4
Mentor 4 GitHub
Mentor 4 email address
```
~~~

I know that not every project in the source will have all the fields filled (\`LFX URL\`, \`project made\`, \`mentee selection\`, and \`mentor count in LFX\` will come later), and there may not be as many as 4 mentors in each project. Please only provide the GitHub handle, no need for the \`@\` at the beginning of it.

The \`PROJECT\` field should have the format of:
\`CNCF - \<CNCF Project Name\>: \<Mentorship project Title\> (2025 Term 1)\`

Here is the source from the https://github.com/cncf/mentoring/blob/main/programs/lfx-mentorship/2025/01-Mar-May/project_ideas.md file:

~~~
```

```
~~~

Please create a .csv file that I can copy and import into Google Sheets. Be careful to ensure that the columns align, this can be tricky with .csv files.
</blockquote>  