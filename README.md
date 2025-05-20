<img src="https://raw.githubusercontent.com/devLucasRamos/devLucasRamos/main/.github/workflows/devlucasgifgit2.gif" alt="">
<a></a>
<img src="https://raw.githubusercontent.com/devLucasRamos/devLucasRamos/main/.github/workflows/yon2.png" alt="">
<a></a>
 
<div> 
  <img height="190" src="https://github-readme-stats.vercel.app/api?username=devLucasRamos&show_icons=true&theme=outrun&include_all_commits=true&count_private=true"/>
  <img height="190" src="https://github-readme-stats.vercel.app/api/top-langs/?username=devLucasRamos&layout=compact&langs_count=7&theme=outrun"/>
</div>

<a></a>

```javascript

const renderDeveloperProfile = () => {
  try {
    const profile = {
      name: "Lucas Ramos",
      title: "Backend & Frontend Developer | Student",
      pronouns: "he/his",
      location: "Pinhais, PR"
    };

    const hardSkills = {
      languages: ["C#", "JavaScript", "HTML", "CSS"],
      frameworks: [".NET", "React", "Angular", "Node.js"],
      databases: ["MySQL", "SQLite"]
    };

    const softSkills = ["Adaptability", "Perseverance", "Teamwork", "Proactivity"];

    const styles = `
      :root {
        --primary-color: #2c3e50;
        --accent-color: #3498db;
        --bg-color: #f4f7fa;
        --card-bg: #ffffff;
      }
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }
      body {
        font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
        background: var(--bg-color);
        color: var(--primary-color);
        line-height: 1.6;
        min-height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 20px;
      }
      .profile-container {
        max-width: 900px;
        width: 100%;
        background: var(--card-bg);
        border-radius: 12px;
        box-shadow: 0 4px 20px rgba(0,0,0,0.1);
        overflow: hidden;
      }
      .header {
        background: var(--primary-color);
        color: white;
        padding: 2rem;
        text-align: center;
      }
      .header h1 {
        font-size: 2.5rem;
        margin-bottom: 0.5rem;
      }
      .header p {
        font-size: 1.1rem;
        opacity: 0.9;
      }
      .content {
        padding: 2rem;
      }
      .section {
        margin-bottom: 2rem;
      }
      .section h2 {
        color: var(--accent-color);
        font-size: 1.5rem;
        margin-bottom: 1rem;
        border-bottom: 2px solid var(--accent-color);
        padding-bottom: 0.25rem;
      }
      .profile-info {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 1rem;
        margin-bottom: 2rem;
      }
      .skills-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        gap: 1.5rem;
      }
      .skill-category {
        background: var(--bg-color);
        padding: 1rem;
        border-radius: 8px;
      }
      ul {
        list-style: none;
      }
      li {
        padding: 0.5rem 0;
        font-size: 1rem;
      }
      li::before {
        content: "• ";
        color: var(--accent-color);
      }
      @media (max-width: 600px) {
        .profile-container {
          margin: 10px;
        }
        .header h1 {
          font-size: 1.8rem;
        }
        .profile-info {
          grid-template-columns: 1fr;
        }
        .skills-grid {
          grid-template-columns: 1fr;
        }
      }
    `;

    const html = `
      <!DOCTYPE html>
      <html lang="en">
      <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Lucas Ramos - Developer Profile</title>
        <style>${styles}</style>
      </head>
      <body>
        <div class="profile-container">
          <div class="header">
            <h1>${profile.name}</h1>
            <p>${profile.title}</p>
            <p>Pronouns: ${profile.pronouns}</p>
            <p>Location: ${profile.location}</p>
          </div>
          <div class="content">
            <div class="section profile-info">
              <div><strong>Pronouns:</strong> ${profile.pronouns}</div>
              <div><strong>Location:</strong> ${profile.location}</div>
            </div>
            <div class="section">
              <h2>Hard Skills</h2>
              <div class="skills-grid">
                <div class="skill-category">
                  <strong>Languages</strong>
                  <ul>${hardSkills.languages.map(lang => `<li>${lang}</li>`).join('')}</ul>
                </div>
                <div class="skill-category">
                  <strong>Frameworks</strong>
                  <ul>${hardSkills.frameworks.map(framework => `<li>${framework}</li>`).join('')}</ul>
                </div>
                <div class="skill-category">
                  <strong>Databases</strong>
                  <ul>${hardSkills.databases.map(db => `<li>${db}</li>`).join('')}</ul>
                </div>
              </div>
            </div>
            <div class="section">
              <h2>Soft Skills</h2>
              <ul>${softSkills.map(skill => `<li>${skill}</li>`).join('')}</ul>
            </div>
          </div>
        </div>
      </body>
      </html>
    `;

    document.documentElement.innerHTML = html;
    return { success: true };
  } catch (error) {
    document.body.innerHTML = `<p style="text-align: center; color: #e74c3c;">Error: ${error.message}</p>`;
    return { success: false, error: error.message };
  }
};

renderDeveloperProfile();

```
  
<div style="display: inline_block"><br>
  
 <img align="left" alt="LR-Gatinho" height="160" width="160" src="https://media2.giphy.com/media/cMF3Fa3ZnLs8jk4xM4/giphy.gif?cid=ecf05e47c5ys25z99vok2qixgk3djran9isg1oslm2kw2gbh&rid=giphy.gif&ct=g">
 
  <img align="center" alt="LR-Csharp"  src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white">
  <img align="center" alt="LR-Js" src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E">
  <img align="center" alt="LR-HTML"  src="https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white">
  <img align="center" alt="LR-CSS3"  src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 

<a></a>

 <img align="center" alt="LR-Dotnet"  src="https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white">
 <img align="center" alt="LR-React"  src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
 <img align="center" alt="LR-Angular"  src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white">
 <img align="center" alt="LR-NodeJS"  src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
 
<a></a>
 
<a></a>

 <img align="center" alt="LR-MySQL"  src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white">
 <img align="center" alt="LR-SQLITE"  src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white">
 
<a></a>
 

 <a href = "mailto:lucas2adriano@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank" ></a>
 <a href="https://www.linkedin.com/in/devlucasramos" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
   <a href="https://www.facebook.com/devLucasRamos/" target="_blank"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" target="_blank"></a> 
 
 
 
</div>
  
![Snake animation](https://github.com/devLucasRamos/devLucasRamos/blob/output/github-contribution-grid-snake.svg)
