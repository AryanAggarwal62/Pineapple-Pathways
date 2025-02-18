# Pineapple Pathways

**Pineapple Pathways** is an AI-powered platform designed to assist students with Ontario university admissions by providing personalized guidance on supplemental applications, scholarship opportunities, admission chances, and tuition costs.

## Overview
Navigating university admissions can be overwhelming, especially with complex supplemental applications, financial considerations, and varying acceptance rates. *Pineapple Pathways* simplifies this process by leveraging AI to offer tailored insights and actionable recommendations, helping students make informed decisions about their future. By consolidating essential resources into a single platform, we empower students with the tools they need to successfully apply to universities and secure scholarships.

## Features

- **Supplemental Application Assistance**: Analyzes and provides specific feedback and tips on application responses to improve clarity and effectiveness.
- **Scholarship Search**: Matches students with relevant scholarships based on eligibility criteria and program selection, utilizing Cohere Rerank to provide the most relevant results from a database of over 500 scholarships.
- **Admission Probability Estimation**: Uses statistical models and publicly available data to assess the likelihood of admission to specific universities and programs.
- **Tuition Cost Display**: Provides accurate tuition estimates for Ontario university programs, factoring in program-specific and additional costs.

## How We Built It

### Backend
- **Scholarship Matching**: Built with Python and Flask, the backend processes user input via JSON requests and leverages the Cohere API to rank scholarships based on relevance.
- **Essay Helper**: A custom-trained ChatGPT model provides detailed feedback to improve user-submitted essays and responses.
- **Admission Statistics**: Utilized university admission data processed from CSV files to calculate acceptance probabilities.
- **Tuition Estimation**: A compiled dataset of tuition costs enables users to estimate expenses based on their selected program and university.

### Frontend
- **Landing Page**: Designed with React, the landing page employs a brutalist aesthetic for a distinctive, eye-catching experience.
- **Dashboard**: Features a minimalistic yet intuitive interface for easy access to all functionalities.

## Challenges We Ran Into
- Learning Flask for backend development, particularly handling user inputs such as checkboxes and dropdowns.
- Difficulties in aligning tuition data with user input for accurate cost estimations.
- Hosting a dynamic website requiring backend communication, ultimately resolved by deploying on Vercel.

## Accomplishments That We're Proud Of
- Successfully implementing Cohere Rerank for consistent and relevant scholarship recommendations.
- Integrating ChatGPT to provide insightful essay feedback.
- Creating a polished, professional UI with an experimental yet user-friendly design.

## What We Learned
Each team member expanded their skill set by learning and implementing:
- Flask
- OpenAI API
- Cohere Rerank
- React
- Web Scraping
- Database Management

## What's Next for Pineapple Pathways
- Expanding our scholarship dataset through web scraping and improved databasing techniques.
- Enhancing the university application insights by integrating additional university statistics.
- Upgrading AI models as newer versions become available for better feedback and prediction accuracy.
- Transitioning to a dedicated domain for improved accessibility and reliability.

## Demo

- **Try It Out**: [Live Demo](https://ai-teacher-njyu-git-main-gorgocaptaingmailcoms-projects.vercel.app/)
- **Learn More**: [Devpost](https://devpost.com/software/pineapple-pathways)

## Built With

- **Flask** - Backend framework  
- **OpenAI API** - AI-powered analysis and feedback generation  
- **Cohere API** - Scholarship ranking  
- **Python** - Core programming language  
- **JavaScript** - Front-end development  
- **ReactJS** - User interface framework  
- **Tailwind CSS** - Styling framework  

## Contributors

- **Aryan Aggarwal** - Backend, OpenAI API Integration, Scholarship Matching, Web Scraping
- **George Florea** - Frontend, React, Tuition Calculator
- **Harit Oza** - Backend
- **Akishai Sabaratnasarma** - Backend, Flask

## Acknowledgments

Special thanks to **Hack the 6ix** for providing the platform and mentorship that made this project possible.

## Contact

For any inquiries or feedback, please reach out to:

- **Aryan Aggarwal** - [LinkedIn](https://www.linkedin.com/in/aryan-aggarwal-/)  
- **George Florea** - [LinkedIn](https://www.linkedin.com/in/george-florea-237499312/)  
- **Harit Oza** - [LinkedIn](https://www.linkedin.com/in/harit-oza/)  
- **Akishai Sabaratnasarma** - [LinkedIn](https://www.linkedin.com/in/akishai/)  

Check out our GitHub repository or Devpost page for more information!

