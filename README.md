# Smart Waste Backend

This is the backend for the Smart Waste Collection System.  
It connects with IoT sensors to check bin fill levels and helps schedule garbage truck routes in a smarter way. The project also includes GitHub Actions CI/CD, AWS EC2 deployment, and PM2 process management.

---

## 7. Discussion and Conclusion

Working on this project gave me a better understanding of how code, automation, and cloud hosting all come together. At the start, I had issues with GitHub Actions workflows (like handling secrets and YAML errors), but once they were fixed, it was rewarding to see the pipeline running successfully and tests passing.  it has been a great experience as well as opportunities to learn all of these things and alwasy receive support from Tanzir. he is a great man. it is very lucky for me to become student in this class since it give me huge chance and support from Tanzir to create projects which i have been tempted to do for a very long time. No matter how the outcome gonna be i really enjoy this subject. 

Deploying the backend to AWS EC2 with PM2 made the app feel “real” — seeing it run on a public IP confirmed everything was wired up properly.  

**Conclusion:**  
The project shows that waste collection can be optimized with IoT and cloud solutions. On the technical side, it taught me how important automation and deployment tools are for building reliable systems.

---

## Reflection

Through this project, I learned how to:  
- Write and run automated tests with Mocha.  
- Set up GitHub Actions for CI/CD.  
- Securely manage secrets in GitHub.  
- Deploy a Node.js backend to AWS EC2 and keep it alive with PM2.  

**Difficulties I faced:**  
- Debugging GitHub Actions YAML errors.  
- Configuring AWS EC2 security groups so the app was accessible from the internet.  
- Making sure PM2 started the backend correctly and showed the right status.  

Overall, the process was sometimes frustrating, but it gave me hands-on skills with CI/CD, deployment, and debugging that I’ll use in future projects.
