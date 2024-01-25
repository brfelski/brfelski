<h2> Hello stranger, you can call me Felski </h2>

<br>

```javascript
function whoIam() {
  const tecnologies = ['js', 'ts', 'java', 'react', 'chackraUI'];
  tecnologies.forEach(tech => {
    while (isStillReleasingUpdates(tech)) {
      return hasSometingToLearn(tech);
    }
  })
}

function hasSometingToLearn(tech) {
    console.log('Learning something new about ' + tech);
}

function isStillReleasingUpdates(tech){
    if (ff <= 10){
        ff = 1;
        return true;
    }
}

whoIam();
```
