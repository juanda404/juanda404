 <h2 align="center">About me </h2>
 
- 🔭 I’m currently working as Freelancer ...
- 🌱 I’m currently learning about React.js...
- ✍🏼 Writer in my personal blog [juanda404](https://mylifeincodeandtraining.blogspot.com/)
- 🌟 Web Developer since 2024.
  
<h2 align="center">Technical Skills </h2>

```
const juanda404 = {
  getTechnicalSkills: () => [
    "React.js",
    "javascript",
    "HTML5",
    "CSS3",
    "TAILWIND CSS",
    "MySQL",
    "C#",
    "CMS Sitefinity",
  ],
};

const AboutMe = () => {
  return (
    <div>
      <h1>About Me</h1>
      <h2>Technical Skills</h2>
      <ul>
        { juanda404.getTechnicalSkills().map((skill, index) => (
          <li key={index}>{skill}</li>
        ))}
      </ul>
    </div>
  );
};

export default AboutMe;
```
<h2 align="center"> Hobby </h2>

"Passionate about gym training, following a disciplined hypertrophy-focused routine every week. 💪🔥"

