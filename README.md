<h1 align="center"> Nicholas Alvi Saputra </h1>

```javascript

import React from "react"

const GetBio = () => {
  const bio = [
    {
      quickBio: ["Tech", "Rhythm Games"],
      workedOn: "ReactJS",
      learning: ["NodeJS", "ReactJS"],
      lang: ["Javascript", "Typescript", "PHP"],
    },
  ]
  return (
    <>
      {bio.map((e, i) => (
        <div key={i}>
          <p>Quick Bio: {e.quickBio.join(", ")}</p>
          <p>Currently Worked on: {e.workedOn}</p>
          <p>Currently Learning on: {e.learning.join(", ")}</p>
          <p>Programming Language: {e.lang.join(", ")}</p>
        </div>
      ))}
    </>
  )
}

export default GetBio
```

<details align="center">

### Hello, thanks for visiting my Github account! 👋

<img align="right" src="https://github-readme-tech-stack.vercel.app/api/cards?lineCount=2&theme=catppuccin_mocha&line1=react%2Creactjs%2C04f5d6%3Bjavascript%2Cjavascript%2Ce1addc%3Bnext.js%2Cnextjs%2C03cdbb%3B&line2=tailwindcss%2Ctailwindcss%2Caaa000%3Bsass%2Csass%2C8715ca%3Bheadlessui%2Cheadlessui%2C8bb4db%3B" alt="My Tech Stack" />

Nicholas Alvi Saputra  
Software Engineer

---

I'm currently self-learning Back-end & Front-end Programming!
Feel free to reach me on [Email](mailto:nicholasalvisaputra@gmail.com "Nicholas's Email") and [Linkedin](https://www.linkedin.com/in/nicholasalvis/ "Nicholas's Linkedin")

</details>
