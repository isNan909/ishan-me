// Executable Javascript Snippet

function Person(
  fullName,
  userName,
  position,
  socialMedia,
  email,
  education,
  code,
  blogWritings,
  summary
) {
  this.fullName = fullName;
  this.userName = userName;
  this.position = position;
  this.socialMedia = socialMedia;
  this.education = education;
  this.code = code;
  this.blogWritings = blogWritings;
  this.summary = summary;
  this.email = email;
}

const myIntroduction = new Person(
  "Ishan Manandhar",
  "ishan-me",
  "Product designer and Frontend developer",
  {
    twitter: "https://twitter.com/ishan02016",
    youtube: "https://www.youtube.com/channel/UCS3-MF_4ADqglU2OSly4vIw",
    dribbble: "https://dribbble.com/ishan-manandhar",
    linkedin: "https://www.linkedin.com/in/ishan-me/",
  },
  "ishan02016@gmail.com",
  [
    "MSc. Design Thinking and Innovation",
    "Bacholers in Information Management",
  ],
  {
    frontend: ["HTML", "CSS", "JavaScript", "React"],
    backend: ["Node"],
    database: ["MongoDB"],
    tools: ["Figma", "Miro", "Insomnia"],
    misc: [
      "Headless CMS (eg: Contentful, Prismic, Strapi)",
      "Framer Motion",
      "Tweenmax",
      "Redux",
    ],
    frameworks: ["Express", "React", "Next", "Gatsby"],
    learning: ["Typescript", "Python"],
  },
  [
    "https://ishan02016.medium.com/design-for-trust-establishing-a-healthy-relationship-with-your-users-87fa3e1a2f2d",
    "https://www.digitalocean.com/community/tutorials/react-crud-context-hooks",
    "https://javascript.plainenglish.io/enable-blazing-gatsby-build-time-with-incremental-builds-6f93935b05c2",
    "https://blog.logrocket.com/using-state-machines-with-xstate-and-react/",
  ],
  "I strongly belive we the professionals of tech industry need to learn and innovate. There is constant change in the technologies in the tech market where we need to update ourselves with. The only thing that is constant is change. Talking about me, I would call myself an intersection of developer(Fr) and designer. I like front-end development with React/Gatsby/Next/Svelte. I love trying out new technologies and update with modern tools helping our lives more easier."
);
