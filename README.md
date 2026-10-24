# MeloLearn — Music Learning Platform

MeloLearn is an interactive web prototype for exploring music education, instrument courses, student performances, and creative learning tools.

## Highlights

- Browse learning options for instruments including violin, flute, piano, guitar, and drums
- Explore course schedules and multimedia lesson content
- Listen to student performances through an integrated music-player experience
- Navigate dedicated learning and music-creation paths
- Use a prototype login and choice flow built with Express routes

## Tech Stack

- HTML5, CSS3, and JavaScript
- Node.js and Express prototype server
- Audio and video media integration
- Responsive page layouts

## Pages

- `home1.html` — landing page and music player
- `index.html` — instrument course catalog
- `login.html` — prototype login interface
- `choice.html` — learning-path selection
- `lecture.html` — learning content
- `tools.html` — music-creation resources

## Run the Front-End Prototype

Clone the repository and open `home1.html` in a browser. For more consistent local media loading, serve the repository with a lightweight static server:

```bash
npx serve .
```

Then open the local address shown in the terminal.

## Prototype Status

This is an academic front-end prototype. The login logic in `server.js` is demonstrative only and does not provide production authentication. Before deployment, the project should be reorganized into a standard public/source structure, the dependency manifest should be replaced with project-specific metadata, and authentication should use secure credential storage and validation.

## Future Improvements

- Responsive and accessible navigation across all pages
- Secure user accounts and persistent course progress
- Search and filtering for instruments and lessons
- Deployment-ready project structure and automated tests
- Optimized media assets and documented content licensing

## Author

**Ulagarchana Ulaga Narasimhan**  
M.S. Computer Science, Arizona State University  
[LinkedIn](https://www.linkedin.com/in/ulagarchana-u) · [GitHub](https://github.com/ulagarchana)
