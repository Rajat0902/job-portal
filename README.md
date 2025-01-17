<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Job Portal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #004080;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 20px;
        }
        .search-bar {
            display: flex;
            justify-content: center;
            margin-bottom: 20px;
        }
        .search-bar input, .search-bar select {
            padding: 10px;
            margin: 0 5px;
        }
        .job-listings {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .job {
            background: white;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #004080;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to the Job Portal</h1>
        <p>Find your dream job or the perfect candidate!</p>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Job Seekers</a>
        <a href="#">Employers</a>
        <a href="#">About Us</a>
        <a href="#">Contact</a>
    </nav>

    <div class="container">
        <!-- Search Bar -->
        <div class="search-bar">
            <input type="text" placeholder="Search jobs...">
            <select>
                <option value="">Location</option>
                <option value="remote">Remote</option>
                <option value="onsite">Onsite</option>
            </select>
            <select>
                <option value="">Job Type</option>
                <option value="full-time">Full-Time</option>
                <option value="part-time">Part-Time</option>
                <option value="freelance">Freelance</option>
            </select>
            <button>Search</button>
        </div>

        <!-- Job Listings -->
        <h2>Featured Jobs</h2>
        <div class="job-listings">
            <div class="job">
                <h3>Software Engineer</h3>
                <p><strong>Company:</strong> Tech Innovators</p>
                <p><strong>Location:</strong> Remote</p>
                <p><strong>Type:</strong> Full-Time</p>
                <button>Apply Now</button>
            </div>
            <div class="job">
                <h3>Graphic Designer</h3>
                <p><strong>Company:</strong> Creative Studio</p>
                <p><strong>Location:</strong> New York, NY</p>
                <p><strong>Type:</strong> Freelance</p>
                <button>Apply Now</button>
            </div>
            <div class="job">
                <h3>Marketing Specialist</h3>
                <p><strong>Company:</strong> MarketPros</p>
                <p><strong>Location:</strong> Onsite</p>
                <p><strong>Type:</strong> Part-Time</p>
                <button>Apply Now</button>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Job Portal. All rights reserved.</p>
    </footer>
</body>
</html>
