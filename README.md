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
          <p>{e.quickBio.join(", ")}</p>
          <p>{e.workedOn}</p>
          <p>{e.learning.join(", ")}</p>
          <p>{e.lang.join(", ")}</p>
        </div>
      ))}
    </>
  )
}

export default GetBio

```

<details align="center">

### Hello, thanks for visiting my Github account! 👋

<img align="right" src="https://github-readme-stats.vercel.app/api?username=kangnikol&show_icons=true&bg_color=1e1e2e&text_color=cdd6f4&icon_color=cba6f7&title_color=94e2d5" />

Nicholas Alvi Saputra  
Software Engineer

---

I'm currently self-learning Back-end & Front-end Programming!
Feel free to reach me on [Email](mailto:nicholasalvisaputra@gmail.com "Nicholas's Email") and [Linkedin](https://www.linkedin.com/in/nicholasalvis/ "Nicholas's Linkedin")

</details>
