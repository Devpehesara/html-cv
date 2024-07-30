# HTML CV Project

This project is a simple HTML-based CV template that you can use to showcase your personal information, educational qualifications, experience, and skills. The template is designed to be easy to customize and align in a neat table format for clear presentation.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Features
- Clean and simple design
- Structured layout using HTML tables
- Easy to customize
- Includes sections for personal information, executive summary, education, experience, and skills
- Links to external resources like LinkedIn and university website

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

You will need a web browser to view the HTML file.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/your_username/html-cv.git
   ```
2. Open `index.html` in your preferred web browser to view your CV.

## Usage

Modify the HTML code to fit your personal information.

### Example HTML Structure

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My CV</title>
</head>

<body>
    <table border="2" align="center">
        <tr>
            <td>
                <table align="center" width="800px">
                    <!-- Personal Information -->
                    <tr>
                        <td>
                            <table border="1">
                                <tr>
                                    <td>
                                        <table align="center" width="800px">
                                            <tr>
                                                <td rowspan="9" align="center">
                                                    <img src="images/dev.jpg" alt="Profile Image" width="200px" border="3">
                                                </td>
                                                <td>
                                                    <h1>A A S Pehesara Dewashmi</h1>
                                                    <ol>
                                                        <li><strong>ADDRESS: </strong>17 Canal, Silva Road, Hingurakgoda</li>
                                                        <li><strong>CONTACT: </strong>0776790618</li>
                                                        <li><strong>E-MAIL: </strong><a href="mailto:pehesara.dewashmi@gmail.com">pehesara.dewashmi@gmail.com</a></li>
                                                        <li><strong>LINKEDIN: </strong><a href="https://www.linkedin.com/in/pehesara-dewashmi-2059572a2">Pehesara Dewashmi</a></li>
                                                        <li><strong>ID: </strong>200261901713</li>
                                                        <li><strong>DATE OF BIRTH: </strong>2002-04-28</li>
                                                        <li><strong>NATIONALITY: </strong>Sri Lankan</li>
                                                        <li><strong>MARITAL STATUS: </strong>Single</li>
                                                    </ol>
                                                </td>
                                            </tr>
                                        </table>
                                    </td>
                                </tr>
                            </table>
                        </td>
                    </tr>
                    <!-- Executive Summary -->
                    <tr>
                        <td>
                            <h2>Executive Summary</h2>
                            <hr width="800px" size="2">
                            <p>Passionate Software Engineering student at Cardiff Metropolitan University. Proficient in various programming languages including Java, Python, and JavaScript. Experienced in software development methodologies. Enthusiastic about problem-solving and learning new technologies. Dedicated team player with strong communication skills. Committed to delivering high-quality solutions.</p>
                        </td>
                    </tr>
                    <!-- Educational Qualification -->
                    <tr>
                        <td>
                            <h2>Educational Qualification</h2>
                            <hr width="800px" size="2">
                            <ul>
                                <li><h3>Higher Education</h3></li>
                                <p>Undergraduated from Cardiff Metropolitan University UK, BSc Software Engineering</p>
                                <a href="https://www.cardiffmet.ac.uk/Pages/default.aspx">Cardiff Metropolitan University - United Kingdom</a>
                            </ul>
                            <table width="800px">
                                <tr>
                                    <td>
                                        <h3>Oridanary Level Exam 2018</h3>
                                        <table border="1" width="250">
                                            <tr><th>Subject</th><th>Result</th></tr>
                                            <tr><td>Sinhala</td><td>A</td></tr>
                                            <tr><td>English</td><td>A</td></tr>
                                            <tr><td>Science</td><td>B</td></tr>
                                            <tr><td>Mathematics</td><td>A</td></tr>
                                            <tr><td>History</td><td>A</td></tr>
                                            <tr><td>Geography</td><td>A</td></tr>
                                            <tr><td>Health & Phy. Edu</td><td>A</td></tr>
                                            <tr><td>Dancing</td><td>A</td></tr>
                                        </table>
                                    </td>
                                    <td>
                                        <h3>G.C.E Advance Level Exam 2022/23</h3>
                                        <table border="1" width="250">
                                            <tr><th>Subject</th><th>Result</th></tr>
                                            <tr><td>Physics</td><td>C</td></tr>
                                            <tr><td>Combined Maths</td><td>B</td></tr>
                                            <tr><td>Chemistry</td><td>S</td></tr>
                                        </table>
                                        <table height="140"></table>
                                    </td>
                                </tr>
                            </table>
                        </td>
                    </tr>
                    <!-- Experience -->
                    <tr>
                        <td>
                            <h2>Experience</h2>
                            <hr width="800px" size="2">
                            <ul>
                                <li><h3>Trainee Cashier</h3></li>
                                <p>Regional Development Bank<br>Hingurakgoda<br>2023 April - 2023 October</p>
                                <ul>
                                    <li>Processed customer transactions accurately and efficiently in a fast-paced retail environment.</li>
                                    <li>Processed returns, exchanges, and refunds in accordance with company policy.</li>
                                    <li>Responsible for handling cash, check, and credit card payments.</li>
                                </ul>
                            </ul>
                        </td>
                    </tr>
                    <!-- Skills -->
                    <tr>
                        <td>
                            <h2>Skills</h2>
                            <hr width="800px" size="2">
                            <ul>
                                <li>Communication skills</li>
                                <li>Teamwork/Collaboration</li>
                                <li>Time management</li>
                                <li>Languages<br>- English<br>- Sinhala</li>
                            </ul>
                        </td>
                    </tr>
                </table>
            </td>
        </tr>
    </table>
</body>

</html>
```

## Customization

- Replace the personal information, contact details, and other placeholders with your actual details.
- Update the image source to your profile picture.
- Modify the education, experience, and skills sections to reflect your own background.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.
