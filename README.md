### Pleasure to see you here, I'm Adam Whitman
```javascript
import React from 'react';
import styles from './styleComponents';

const Adam = () => {
  const [career, setCareer] = useState('In transition');
  const [mission, setMission] = useState('Improve biomechanical analysis of patients' movements to find the origin of the problem, not just the location of the pain');
  
  const code = () => {
    let languages: ['JavaScript', 'HTML', 'CSS', 'JQuery',];
    let frontEnd: ['React', 'React-Native', 'React Navigation', 'CSS Modules', 'Webpack', 'Babel', 'Axios',];
    let backEnd: ['Node', 'Express', 'PostgreSQL', 'MySQL', 'NGINX',];
    
    return languages.concat(frontEnd, backEnd);
  }
  
  const nonTechnicalSkills = () => {
    const publicSpeaking = true;
    const businessManagerialExperience = true;
    let programManagerExperience = 1;
    
    let assetsToAnEmployer = [];
    
    for (let i = 0; i < skills.length; i++) {
      if (skills[i] === 'true' || skills[i] > 0) {
        assetsToAnEmployer.push(skills[i]);
      }
    }
    
    return assetsToAnEmployer;
  }
  
  const acquireSkills = () => {
    let workingOnLearning = 'TypeScript', 
  
    if (!known) {
      return 'Currently planned languages to learn: ' + workingOnLearning;
    }
  }
  
  return (
    <div>
      <div className={styles.nameAndTitle}>
        <h1>Adam Whitman, DPT<h1>
      </div>
      <div className={styles.technical}>
        <h2>{code()}</h2>
      </div>
      <div className={}>
        <h2>{acquireSkills()}</h2>
      </div>
      <div className={styles.nonTechnical}>
        <h3>{nonTechnicalSkills}</h3>
      </div>
      <div className={styles.funFacts}>
        <h5>{funFacts()}</h5>
      </div>
    <div>
  );
};
```

<!--
**emagdaeh/emagdaeh** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
