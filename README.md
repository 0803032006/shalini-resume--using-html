# shalini-resume--using-html


<!DOCTYPE html>
<html >
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to KCE</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }

        header {
            text-align: center;
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
        }

        header img {
            width: 100px;
            height: auto;
        }

        .container {
            max-width: 900px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            border-radius: 8px;
        }

        .profile {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }

        .profile img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-right: 20px;
        }

        .profile-info {
            line-height: 1.6;
        }

        .section {
            margin-top: 20px;
        }

        .section h2 {
            background-color: #4CAF50;
            color: white;
            padding: 10px;
            border-radius: 4px;
        }

        .qualification-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
        }

        .qualification-table th, .qualification-table td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: center;
        }

        .qualification-table th {
            background-color: #4CAF50;
            color: white;
        }

        .buttons {
            text-align: center;
            margin-top: 20px;
        }

        .buttons button {
            padding: 10px 20px;
            margin: 5px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        .buttons button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to KCE</h1>
        <img src="c:\Users\kvign\OneDrive\Documents\download.jpeg" alt="KCE Logo">
    </header>

    <div class="container">
        <div class="profile">
            <img src="C:\Users\kvign\OneDrive\Pictures\Camera imports\2024-12-20\Screenshot_2024-08-12-21-47-08-51_965bbf4d18d205f782c6b8409c5773a4~2.jpg" alt="Profile Photo">
            <div class="profile-info">
                <p><strong>Name:</strong> SHALINI G</p>
                <p><strong>Email:</strong>shalinianu0303@gmail.com</p>
                <p><strong>Phone:</strong> 8825608542</p>
            </div>
        </div>

        <div class="section">
            <h2>Objective</h2>
            <p>
                To secure a challenging position in a forward-thinking organization where I can leverage my skills, foster professional growth, and contribute to achieving organizational goals with innovation and dedication.</p>
        </div>

        <div class="section">
            <h2>Academic Qualification</h2>
            <table class="qualification-table">
                <tr>
                    <th>Degree </th>
                    <th>School/College</th>
                    <th>Percentage</th>
                </tr>
                <tr>
                    <td>B.Tech Artificilal intelligence and data science </td>
                    <td> Karpagam College Of Enginerring</td>
                    <td> 8.5 CGPA</td>
                </tr>
                <tr>
                    <td>10</td>
                    <td>Govt Hss Scholl Kurubarapalli</td>
                    <td>90%</td>
                </tr>
                <tr>
                    <td>12</td>
                    <td> Govt Hss Girls  School</td>
                    <td>85%</td>
                </tr>
            </table>
        </div>

        <div class="section">
            <h2>Certifications</h2>
            <p>Nptel</p>
            <p>great learning certficate</p>
            <p>orcle</p>
            <p>coursera</p>
        </div>

        <div class="section">
            <h2>Internship</h2>
            <p>prodigy info tech </p>
            <P>"I successfully completed a 1-month machine learning internship at Prodigy Infotech, where I gained hands-on experience in developing and deploying ML models. During this period, I worked on real-world datasets, utilizing techniques like data preprocessing, clustering, and classification to derive actionable insights. My key project involved implementing K-means clustering to analyze retail customer behavior effectively. The internship enhanced my proficiency in Python, machine learning libraries, and problem-solving skills. It provided me with valuable exposure to industry practices and strengthened my ability to tackle complex ML challenges."</P>
            <p></p>
        </div>

        <div class="section">
            <h2>Project</h2>
            <p><strong>Project:</strong>Autism prediction</p>
            <p> 
                Autism spectrum disorder (ASD) datasets are analyzed using machine learning to identify patterns and predict the likelihood of autism in individuals. These datasets often include demographic, behavioral, and diagnostic features. By leveraging algorithms such as classification and clustering, ML models help improve early detection and personalized interventions. The analysis enables data-driven insights for better understanding and managing ASD.</p>
        </div>

        <div class="section">
            <h2>PERSONAL DETAILS</h2>
            <p>NAME:Shalini G</p>
            <p> FATHER'S NAME:Govindharaj </p>
            <p> DATE OF BIRTH: 03.03.2006</p>
            <p> QUALIFICATION:B.Tech AIDS </p>
            <P> EXPERIENCE: Freshers</P>
            <p> LANGUAGE KNOWN:Tamil,English,Kanada</p>
            <p>PEFERENCE :my previous employee Mr.Ravi</p>
            <p>SALARY:20000</p>
        </div>

        <div class="section">
            <h2>Declaration</h2>
            <p>"I hereby declare that all the information provided above is true and correct to the best of my knowledge and belief. I take full responsibility for the accuracy of the details mentioned and am ready to provide any necessary documentation to support the same."

                You can personalize it further if needed!</p>
        </div>

        <div class="buttons">
            <button onclick="previousPage()">Back</button>
            <button onclick="nextPage()">Next</button>
        </div>
    </div>

    <script>
        function nextPage() {
            alert('Navigating to the next page!');
        }

        function previousPage() {
            alert('Navigating to the previous page!');
        }
    </script>
</body>
</html>
