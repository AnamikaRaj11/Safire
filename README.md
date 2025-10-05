<!-- # Safire

This browser extension detects and hides harassment messages to create a safer online experience for professional platforms like LinkedIn.

## 🎥 Demo Video (click to play)

[![Watch the demo](extension/assets/screenshots/client-updated-ui.png)]([https://youtu.be/P_AOuIpOxos](https://youtu.be/P_AOuIpOxos))

...
 -->

<div align="center">

  <a href="https://safire-five.vercel.app/" target="_blank">
    <img src="https://raw.githubusercontent.com/aditya-bagret/Safire/main/client/src/assets/Safire.svg" alt="Safire Logo" width="250"/>
  </a>

  <h1 align="center">Safire - The Harassment Saver</h1>
  <p align="center">
    A real-time, AI-powered browser extension to detect, hide, and document online harassment, 
    <br />
    creating a safer digital space for everyone.
    
  </p>

  <p align="center">
    <a href="https://github.com/aditya-bagret/Safire/stargazers"><img src="https://img.shields.io/github/stars/aditya-bagret/Safire?style=for-the-badge&logo=github&color=ce93d8" alt="Stars"></a>
    <a href="https://github.com/aditya-bagret/Safire/network/members"><img src="https://img.shields.io/github/forks/aditya-bagret/Safire?style=for-the-badge&logo=github&color=81d4fa" alt="Forks"></a>
    <img src="https://img.shields.io/badge/Hackathon-WINNER-gold?style=for-the-badge&logo=trophy" alt="Hackathon Winner">
  </p>

  <p align="center">
    <a href="https://safire-five.vercel.app/"><strong>View the Website</strong></a>
    ·
    <a href="#-demo-video">Watch Demo</a>
    ·
    <a href="https://github.com/aditya-bagret/Safire/issues/new?assignees=&labels=bug&template=bug_report.md&title=">Report a Bug</a>
    ·
    <a href="https://github.com/aditya-bagret/Safire/issues/new?assignees=&labels=enhancement&template=feature_request.md&title=">Request a Feature</a>
  </p>

</div>

---

## Demo Video

See Safire in action. Our demo shows how we seamlessly detect harassment, hide messages, and generate legal reports in real-time.

<div align="center">
  <a href="https://youtu.be/P_AOuIpOxos" target="_blank">
    <img src="extension/assets/screenshots/client-updated-ui.png" alt="Watch the Safire Demo" width="800">
  </a>
  <br>
  <em>(Click the thumbnail to watch the full demo on YouTube)</em>
</div>

---

## Getting Started: Local Setup

To get a local copy of Safire up and running on your machine, follow these simple steps.

### Prerequisites

- [*Node.js*](https://nodejs.org/) (v18 or higher recommended)  
- [*pnpm*](https://pnpm.io/installation)  
- [*MongoDB*](https://www.mongodb.com/)  

### Installation & Setup

#### 1. Clone the Repository

```sh
git clone https://github.com/aditya-bagret/Safire.git
cd Safire
```


#### 2. Choose a Project Component

This is a *monorepo* that contains several independent components:

| Directory            | Description                           | Setup Guide                                                  |
| -------------------- | ------------------------------------- | ------------------------------------------------------------ |
| client/            | Public-facing landing page            | [client/README.md](client/README.md)                       |
| dashboard/         | User dashboard web application        | [dashboard/README.md](dashboard/README.md)                 |
| extension/         | Chrome browser extension              | [extension/README.md](extension/README.md)                 |
| server/            | Main backend API                      | [server/README.md](server/README.md)                       |
| moderation-server/ | AI-based text moderation microservice | [moderation-server/README.md](moderation-server/README.md) |


#### 3. Set Up a Component

Navigate into the component you'd like to work on and follow its README for full setup instructions.

For example, to set up the *browser extension*, run:

sh
cd extension
pnpm install
pnpm dev


Then follow the rest of the [extension's README](extension/README.md) to load it in Chrome.



> 💡 Each component is self-contained and can be developed/tested independently.

---

<!-- ## Contributors

This project was brought to life by the team "Smooth Operators".

| Name               | GitHub Profile                               |
| ------------------ | -------------------------------------------- |
| *Aditya Sharma*  | [@aditya-bagret](https://github.com/aditya-bagret)     |
| *Anamika Raj* | [@AnamikaRaj11](https://github.com/AnamikaRaj11) |
| *pari gupta*| [@pg3010-cyber](  https://github.com/pg3010-cyber)|
| *Sugndha Agarwal*| [@SugandhaAgarwal35]( https://github.com/SugandhaAgarwal35)       |

--- -->


## The Team

This project was brought to life by the *"Smooth Operators"*.

<table>
<tr>
<td align="center">
  <a href="https://github.com/aditya-bagret">
    <img src="https://github.com/aditya-bagret.png" width="100px;" alt="Aditya Sharma"/>
    <br />
    <sub><b>Aditya Sharma</b></sub>
  </a>
</td>
<td align="center">
  <a href="https://github.com/AnamikaRaj11">
    <img src="https://github.com/AnamikaRaj11.png" width="100px;" alt="Anamika Raj"/>
    <br />
    <sub><b>Anamika Rajl</b></sub>
  </a>
</td>
<td align="center">
  <a href="https://github.com/pg3010-cyber">
    <img src="https://github.com/pg3010-cyber.png" width="100px;" alt="Pari Gupta"/>
    <br />
    <sub><b>Pari Gupta</b></sub>
  </a>
</td>
<td align="center">
  <a href="https://github.com/SugandhaAgarwal35">
    <img src="https://github.com/SugandhaAgarwal35.png" width="100px;" alt="SugandhaAgarwal"/>
    <br />
    <sub><b>Sugandha Agarwal</b></sub>
  </a>
</td>
</tr>
</table>

---

> [!NOTE]
> *A Note on Our Development Journey*
> 
> As a project born from the fast-paced and dynamic environment of multiple hackathons, our codebase was migrated between private repositories several times during its initial development. This was necessary to meet deadlines and adapt to evolving requirements.
> 
> Consequently, the commit history visible here doesn't fully capture the extensive, iterative process and the hundreds of commits that went into building Safire from the ground up. The current history reflects the final, polished state of the project as we prepared it for the public.
> 
> We share this note to provide context on our journey and to give a nod to the immense effort, late nights, and passion our team poured into bringing this idea to life.

---

