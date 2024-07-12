<div style="display: flex; justify-content: space-between; height: 100vh; overflow: hidden;">
  <div style="width: 70%; padding: 40px; overflow-y: auto;">
    <h1 style="font-size: 2.5em; margin-bottom: 30px;">My Portfolio</h1>

    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 30px; margin-top: 30px;">
      <a href="https://github.com/yourusername/webapp" style="text-decoration: none; color: inherit;">
        <div style="text-align: center; transition: transform 0.3s;">
          <img src="https://via.placeholder.com/400x300.png?text=Web+App" alt="Web App" style="width: 100%; height: auto; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
          <p style="font-size: 1.2em; margin-top: 10px;">Web App</p>
        </div>
      </a>
      <a href="https://github.com/yourusername/mobileapp" style="text-decoration: none; color: inherit;">
        <div style="text-align: center; transition: transform 0.3s;">
          <img src="https://via.placeholder.com/400x300.png?text=Mobile+App" alt="Mobile App" style="width: 100%; height: auto; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
          <p style="font-size: 1.2em; margin-top: 10px;">Mobile App</p>
        </div>
      </a>
      <a href="https://github.com/yourusername/dataviz" style="text-decoration: none; color: inherit;">
        <div style="text-align: center; transition: transform 0.3s;">
          <img src="https://via.placeholder.com/400x300.png?text=Data+Viz" alt="Data Visualization" style="width: 100%; height: auto; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
          <p style="font-size: 1.2em; margin-top: 10px;">Data Visualization</p>
        </div>
      </a>
    </div>
  </div>

  <div style="width: 30%; background-color: #f8f8f8; padding: 40px; box-shadow: -5px 0 15px rgba(0,0,0,0.1); overflow-y: auto; transform: translateX(20%); transition: transform 0.5s;">
    <h2 style="font-size: 2em; margin-bottom: 20px;">About Me</h2>
    <p style="font-size: 1.1em; line-height: 1.6;">I'm a passionate developer with expertise in web and mobile applications. I love creating intuitive, user-friendly interfaces and working with data.</p>

    <h3 style="font-size: 1.5em; margin-top: 30px;">Skills</h3>
    <ul style="font-size: 1.1em; line-height: 1.6;">
      <li>HTML/CSS</li>
      <li>JavaScript</li>
      <li>React</li>
      <li>Node.js</li>
      <li>Python</li>
      <li>Data Analysis</li>
    </ul>

    <h2 style="font-size: 2em; margin-top: 40px;">Contact</h2>
    <ul style="list-style-type: none; padding: 0; font-size: 1.1em; line-height: 1.6;">
      <li>Email: your.email@example.com</li>
      <li>LinkedIn: <a href="https://www.linkedin.com/in/yourname">Your Name</a></li>
      <li>GitHub: <a href="https://github.com/yourusername">@yourusername</a></li>
    </ul>

    <p style="font-size: 1.1em; line-height: 1.6;">Feel free to reach out if you have any questions or would like to collaborate!</p>
  </div>
</div>

<script>
document.addEventListener('DOMContentLoaded', (event) => {
  setTimeout(() => {
    document.querySelector('div[style*="transform: translateX(20%)"]').style.transform = 'translateX(0)';
  }, 500);
});
</script>
