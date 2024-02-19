
# Dribble design

This is a dribble design, converted to a React js 18.2.0 app.  

## Run Locally 

Project Setup and Planning 
Initialize a React Application: Use Create React App to set up a new project.


```bash 
npx create-react-app spur-fit-frontend
cd spur-fit-frontend

  
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install 
  npm install tailwindcss postcss autoprefixer
  npx tailwindcss init -p

```

Start the server

```bash
  npm start
```

### Building the Webpage

1. **Create Components**: Break down your layout into components. For a basic page, you might have components like `Header`, `MainContent`, and `Footer`.
2. **Develop Components**: Start with static HTML structures in each component and style them using Tailwind CSS.
3. **Add Content**: Populate these components with relevant content. Since assets are not provided, you may use placeholder images or create simple graphics. 

### Adding Interactivity and Animations

1. **Choose an Animation Library**: Based on the suggestion, explore libraries like GreenSock (GSAP) or Framer Motion. Let's use GSAP for this example.
    
    ```bash
    npm install gsap
    
    ```
    
2. **Implement Animations**: Add basic animations like fading in content, animating elements on scroll, etc. Start simple and gradually add more complexity.

### Refining UI and UX

1. **Responsive Design**: Ensure your website is responsive. Test on different screen sizes and make adjustments as needed.
2. **User Experience**: Pay attention to the user journey. The UI should be intuitive and engaging.

### Code Quality and Best Practices

1. **Code Review**: Review your code for cleanliness and organization. Use proper naming conventions and keep your code DRY (Don't Repeat Yourself).
2. **Optimization**: Optimize for performance. Ensure images are optimized, and the website loads efficiently.
### Version Control and Deployment

1. **Git Repository**: Initialize a git repository and make regular commits with meaningful messages.
    
    ```bash
    git init
    git add .
    git commit -m "Initial commit"
    
    ```
    
2. **GitHub**: Create a repository on GitHub and push your local repository.
3. **Deployment**: Choose a platform like Netlify or Vercel for deployment. Follow their documentation to deploy your React app.
4. **[README.md](http://readme.md/)**: Write a comprehensive [README.md](http://readme.md/) explaining your project, setup instructions, and any other relevant information.

### Submission

- Submit your GitHub repository link.
- Ensure the live website link is included in your GitHub repository, preferably in the [README.md](http://readme.md/). 
- **Refer to the below examples to add animations using GSAP:**
    1. https://bitworking.github.io/react-gsap/src-components-scroll-trigger
    2. https://stackblitz.com/edit/react-gsap-scroll-trigger?file=index.tsx
    3. https://codepen.io/GreenSock/pen/abyVpNN
    4. https://codepen.io/GreenSock/pen/gOzxzqv
    5. https://codepen.io/dev_loop/pen/zYvmRvq 

**Sourcing assets like images and data for your project is a key step, especially when they're not provided. Here are some resources where you can find high-quality, free-to-use assets:**

- Images and Graphics
    1. **Pexels ([pexels.com](https://www.pexels.com/))**: Another great resource for free stock photos and videos, contributed by talented creators.
    2. **Freepik ([freepik.com](https://www.freepik.com/))**: A platform for free vectors, stock photos, PSDs, and icons.
- Data for Prototyping
    1. **Mockaroo ([mockaroo.com](https://www.mockaroo.com/))**: A useful tool for generating custom mock data in various formats, helpful for simulating real data in your project.
    2. **JSONPlaceholder ([jsonplaceholder.typicode.com](https://jsonplaceholder.typicode.com/))**: A free online REST API that you can use to fetch fake data for testing and prototyping.
- Fonts
    1. **Google Fonts ([fonts.google.com](https://fonts.google.com/))**: Offers a wide array of free and easy-to-embed fonts.
- Icons
    1. **FontAwesome ([fontawesome.com](https://fontawesome.com/))**: A popular icon set and toolkit with free and paid options.
    2. **Ionicons ([ionicons.com](https://ionicons.com/))**: Open-sourced icons crafted for web, iOS, Android, and desktop apps.
- UI Design Inspiration
    1. **Dribbble ([dribbble.com](https://dribbble.com/))**: A community of designers sharing screenshots of their work, process, and projects.
