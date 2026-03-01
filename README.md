
```ts
/**
 * ashil.ts
 *
 * Full-stack & mobile developer.
 * I build things that feel good to use.
 *
 * Kerala, India  ·  Open to work  ·  github.com/4shil
 */

type Stack = {
  languages : string[]
  mobile    : string[]
  web       : string[]
  backend   : string[]
  tools     : string[]
}

type Project = {
  name    : string
  tagline : string
  stack   : string[]
  link    : string
  live?   : string
}

type Developer = {
  name      : string
  based     : string
  currently : string
  stack     : Stack
  projects  : Project[]
  approach  : string
  contact   : string
}

// ─────────────────────────────────────────────────────────────────────────────

const ashil: Developer = {

  name  : "Ashil",
  based : "Kerala, India 🌴",

  currently : "shipping Atlas to the App Store",

  stack: {
    languages : ["TypeScript", "Python", "Kotlin", "Go", "JavaScript"],
    mobile    : ["React Native", "Expo", "Android"],
    web       : ["Next.js", "React", "Three.js", "Tailwind CSS", "GSAP"],
    backend   : ["FastAPI", "Supabase", "AWS S3", "Docker"],
    tools     : ["MediaPipe", "OpenCV", "FFmpeg.wasm", "MindAR"],
  },

  projects: [
    {
      name    : "Atlas",
      tagline : "Bucket list app. Set goals. Map your life.",
      stack   : ["React Native", "Expo", "Supabase", "TypeScript"],
      link    : "https://github.com/4shil/Atlas",
    },
    {
      name    : "KineMouse",
      tagline : "Your hand is the mouse. No hardware needed.",
      stack   : ["Python", "MediaPipe", "OpenCV"],
      link    : "https://github.com/4shil/kinemouse",
    },
    {
      name    : "DeonAi",
      tagline : "Terminal-style AI chat. Multi-model. Fast.",
      stack   : ["Next.js", "FastAPI", "Supabase"],
      link    : "https://github.com/4shil/DeonAi",
    },
    {
      name    : "Axium",
      tagline : "File transfer that self-destructs after delivery.",
      stack   : ["Next.js", "AWS S3", "TypeScript"],
      link    : "https://github.com/4shil/Axium-TempFiles",
      live    : "https://axium-vvwg.onrender.com",
    },
    {
      name    : "Giffy",
      tagline : "Video → GIF. Runs in your browser. Stays on your device.",
      stack   : ["FFmpeg.wasm", "TypeScript"],
      link    : "https://github.com/4shil/Giffy",
      live    : "https://giffy-sand-kappa.vercel.app",
    },
    {
      name    : "MemoryLink AR",
      tagline : "Scan a Polaroid. The memory plays in AR.",
      stack   : ["Next.js", "Three.js", "MindAR"],
      link    : "https://github.com/4shil/MemoryLink-AR",
    },
    {
      name    : "Password Manager",
      tagline : "Zero-knowledge vault. Nothing leaves your device.",
      stack   : ["Next.js", "TypeScript"],
      link    : "https://github.com/4shil/Password-Manager",
      live    : "https://zkpasskeeper.vercel.app",
    },
    {
      name    : "Musicya",
      tagline : "Offline Android music player. Neo-Brutalist. LRC lyrics.",
      stack   : ["Kotlin", "Android"],
      link    : "https://github.com/4shil/Musicya",
    },
  ],

  approach : "Design it first. Then engineer it to match.",
  contact  : "github.com/4shil",

}

export default ashil
```

---

<div align="center">

[![github stats](https://github-readme-stats.vercel.app/api?username=4shil&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e&icon_color=58a6ff&hide=contribs&rank_icon=github)](https://github.com/4shil)
&nbsp;
[![top langs](https://github-readme-stats.vercel.app/api/top-langs/?username=4shil&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e)](https://github.com/4shil)

[![streak](https://streak-stats.demolab.com?user=4shil&theme=dark&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff)](https://github.com/4shil)

</div>
