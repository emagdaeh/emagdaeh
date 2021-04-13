### Pleasure to meet you, I'm Adam Whitman
```javascript
import React from 'react';
import styles from './styleComponents/Introduction.module.css';

const Adam = () => {
  const [career, setCareer] = useState('In transition');
  const [mission, setMission] = useState('Use tech to improve biomechanical analsysis of patient movement faults');
  
  const technicalSkills = () => {
    const languages: ['JavaScript', 'HTML', 'CSS', 'JQuery',];
    const frontEnd: ['React', 'React-Native', 'React Navigation', 'CSS Modules', 'Webpack', 'Babel', 'Axios',];
    const backEnd: ['Node', 'Express'];
    const devOps: ['AWS', 'Docker', 'Nginx'];
    const databases: ['MongoDB', 'MySQL', 'PostgreSQL'];
    
    return languages.concat(frontEnd, backEnd, devOps, databases);
  }
  
  const nonTechnicalSkills = () => {
    const clientNegotiation = true;
    const leadershipExperience = true;
    const productManagerExperience = 1;
    
    let assetsToAnEmployer = [];
    
    for (let i = 0; i < skills.length; i++) {
      if (skills[i] === 'true' || skills[i] > 0) {
        assetsToAnEmployer.push(skills[i]);
      }
    }
    
    return assetsToAnEmployer;
  }
  
  const acquireSkills = () => {
    const workingOnLearning = 'TypeScript, GraphQL, SwiftUI, Flutter'; 
  
    if (!known) {
      return 'Currently planned languages to learn: ' + workingOnLearning;
    }
  }
  
  const funFacts = () => {
    const fact1 = 'Provides concierge physical therapy for NFL athletes';
    const fact2 = 'Gamer nerd, especially tabletop RPGs';
    const fact3 = 'Aboslutely loves public speaking and teaching, particularly regarding the human body and movement';
    
    return fact1 + ', ' + fact2 + ', and ' + fact3;
  }
  
  return (
    <div>
      <div className={styles.nameAndTitle}>
        <h1>Adam Whitman, DPT<h1>
      </div>
      <div className={styles.technical}>
        <h2>{technicalSkills()}</h2>
      </div>
      <div className={styles.workingOnIt}>
        <h2>{acquireSkills()}</h2>
      </div>
      <div className={styles.nonTechnical}>
        <h3>{nonTechnicalSkills()}</h3>
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
