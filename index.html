<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College Finder - Find Your Perfect College Match</title>
    <style>
        :root {
            --primary: #2a4365;
            --secondary: #3182ce;
            --accent: #f6ad55;
            --light: #f7fafc;
            --dark: #1a202c;
            --success: #48bb78;
            --error: #e53e3e;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f7fafc;
            color: var(--dark);
            line-height: 1.6;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            padding: 2rem 0;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        header p {
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto;
        }
        
        nav {
            background-color: white;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        nav ul {
            display: flex;
            list-style: none;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 1rem;
        }
        
        nav li {
            padding: 1rem;
        }
        
        nav a {
            color: var(--primary);
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        nav a:hover {
            color: var(--secondary);
        }
        
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }
        
        .search-section {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 2rem;
            margin-bottom: 2rem;
        }
        
        .search-section h2 {
            margin-bottom: 1.5rem;
            color: var(--primary);
        }
        
        .search-filters {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 1.5rem;
            margin-bottom: 1.5rem;
        }
        
        .filter-group {
            display: flex;
            flex-direction: column;
        }
        
        .filter-group label {
            margin-bottom: 0.5rem;
            font-weight: 500;
        }
        
        .filter-group select,
        .filter-group input {
            padding: 0.75rem;
            border: 1px solid #cbd5e0;
            border-radius: 4px;
            font-size: 1rem;
        }
        
        .search-section button {
            background-color: var(--secondary);
            color: white;
            border: none;
            border-radius: 4px;
            padding: 0.75rem 1.5rem;
            font-size: 1rem;
            font-weight: 500;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        
        .search-section button:hover {
            background-color: var(--primary);
        }
        
        .results-section {
            margin-top: 2rem;
        }
        
        .college-card {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            margin-bottom: 1.5rem;
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .college-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
        }
        
        .college-header {
            background-color: var(--primary);
            color: white;
            padding: 1.5rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .college-header h3 {
            margin: 0;
            font-size: 1.3rem;
        }
        
        .college-header .match {
            background-color: var(--accent);
            color: var(--dark);
            padding: 0.25rem 0.75rem;
            border-radius: 20px;
            font-weight: 600;
            font-size: 0.9rem;
        }
        
        .college-body {
            padding: 1.5rem;
        }
        
        .college-stats {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            margin-bottom: 1rem;
            padding-bottom: 1rem;
            border-bottom: 1px solid #e2e8f0;
        }
        
        .stat {
            text-align: center;
            padding: 0.5rem;
        }
        
        .stat-label {
            font-size: 0.875rem;
            color: #718096;
        }
        
        .stat-value {
            font-size: 1.25rem;
            font-weight: 600;
            color: var(--primary);
        }
        
        .college-courses {
            margin-bottom: 1rem;
        }
        
        .college-courses h4 {
            color: var(--primary);
            margin-bottom: 0.5rem;
        }
        
        .course-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
        }
        
        .course-tag {
            background-color: #e2e8f0;
            color: var(--dark);
            padding: 0.25rem 0.75rem;
            border-radius: 20px;
            font-size: 0.9rem;
        }
        
        .college-actions {
            display: flex;
            justify-content: space-between;
            margin-top: 1rem;
        }
        
        .college-actions button {
            background-color: var(--secondary);
            color: white;
            border: none;
            border-radius: 4px;
            padding: 0.5rem 1rem;
            font-size: 0.9rem;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        
        .college-actions button:hover {
            background-color: var(--primary);
        }
        
        .college-actions .save-btn {
            background-color: transparent;
            color: var(--primary);
            border: 1px solid var(--primary);
        }
        
        .college-actions .save-btn:hover {
            background-color: #edf2f7;
        }
        
        .featured-section {
            margin-top: 3rem;
            margin-bottom: 3rem;
        }
        
        .featured-section h2 {
            margin-bottom: 1.5rem;
            color: var(--primary);
            text-align: center;
        }
        
        .featured-cards {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 1.5rem;
        }
        
        .featured-card {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .featured-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
        }
        
        .featured-card-img {
            height: 150px;
            width: 100%;
            background-color: #a0aec0;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 1.5rem;
            font-weight: 600;
        }
        
        .featured-card-body {
            padding: 1.5rem;
        }
        
        .featured-card h3 {
            margin-bottom: 0.5rem;
            color: var(--primary);
        }
        
        .featured-card p {
            color: #4a5568;
            margin-bottom: 1rem;
        }
        
        .featured-card a {
            color: var(--secondary);
            text-decoration: none;
            font-weight: 500;
            display: inline-block;
        }
        
        .featured-card a:hover {
            text-decoration: underline;
        }
        
        .resources-section {
            margin-top: 3rem;
            padding: 2rem;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        .resources-section h2 {
            margin-bottom: 1.5rem;
            color: var(--primary);
        }
        
        .resources-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 1.5rem;
        }
        
        .resource-card {
            border: 1px solid #e2e8f0;
            border-radius: 8px;
            padding: 1.5rem;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .resource-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
        }
        
        .resource-card h3 {
            margin-bottom: 0.5rem;
            color: var(--primary);
        }
        
        .resource-card p {
            color: #4a5568;
            margin-bottom: 1rem;
        }
        
        .resource-card a {
            color: var(--secondary);
            text-decoration: none;
            font-weight: 500;
            display: inline-block;
        }
        
        .resource-card a:hover {
            text-decoration: underline;
        }
        
        footer {
            background-color: var(--dark);
            color: white;
            padding: 2rem 0;
            margin-top: 3rem;
        }
        
        .footer-content {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 1rem;
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 2rem;
        }
        
        .footer-column h3 {
            margin-bottom: 1rem;
            font-size: 1.2rem;
        }
        
        .footer-column ul {
            list-style: none;
        }
        
        .footer-column li {
            margin-bottom: 0.5rem;
        }
        
        .footer-column a {
            color: #a0aec0;
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .footer-column a:hover {
            color: white;
        }
        
        .footer-bottom {
            max-width: 1200px;
            margin: 0 auto;
            padding: 1rem;
            text-align: center;
            border-top: 1px solid #2d3748;
            margin-top: 2rem;
            color: #a0aec0;
            font-size: 0.875rem;
        }
        
        /* Modal */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.7);
            z-index: 1000;
        }
        
        .modal-content {
            background-color: white;
            border-radius: 8px;
            max-width: 600px;
            margin: 5% auto;
            padding: 2rem;
            position: relative;
            max-height: 90vh;
            overflow-y: auto;
        }
        
        .close-btn {
            position: absolute;
            top: 1rem;
            right: 1rem;
            font-size: 1.5rem;
            color: #a0aec0;
            cursor: pointer;
            transition: color 0.3s;
        }
        
        .close-btn:hover {
            color: var(--dark);
        }
        
        .modal h2 {
            margin-bottom: 1.5rem;
            color: var(--primary);
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
            }
            
            nav li {
                padding: 0.5rem 1rem;
            }
            
            .search-filters {
                grid-template-columns: 1fr;
            }
            
            .college-header {
                flex-direction: column;
                align-items: flex-start;
            }
            
            .college-header .match {
                margin-top: 0.5rem;
            }
            
            .college-stats {
                flex-direction: column;
                align-items: flex-start;
            }
            
            .stat {
                display: flex;
                justify-content: space-between;
                width: 100%;
                padding: 0.25rem 0;
            }
            
            .college-actions {
                flex-direction: column;
                gap: 0.5rem;
            }
            
            .college-actions button {
                width: 100%;
            }
            
            .featured-cards {
                grid-template-columns: 1fr;
            }
            
            .footer-content {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>College Finder</h1>
        <p>Find your perfect college match based on your interests, desired courses, and career goals</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#search">Search Colleges</a></li>
            <li><a href="#resources">Resources</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <div class="container">
        <section id="search" class="search-section">
            <h2>Find Your Perfect College</h2>
            <div class="search-filters">
                <div class="filter-group">
                    <label for="major">Field of Study / Major</label>
                    <select id="major">
                        <option value="">Select Major</option>
                        <option value="computer-science">Computer Science</option>
                        <option value="engineering">Engineering</option>
                        <option value="business">Business</option>
                        <option value="arts">Arts & Humanities</option>
                        <option value="health">Health Sciences</option>
                        <option value="social-sciences">Social Sciences</option>
                        <option value="education">Education</option>
                        <option value="law">Law</option>
                        <option value="medicine">Medicine</option>
                    </select>
                </div>
                
                <div class="filter-group">
                    <label for="location">Location</label>
                    <select id="location">
                        <option value="">Select Location</option>
                        <option value="northeast">Northeast</option>
                        <option value="southeast">Southeast</option>
                        <option value="midwest">Midwest</option>
                        <option value="southwest">Southwest</option>
                        <option value="west">West</option>
                        <option value="international">International</option>
                    </select>
                </div>
                
                <div class="filter-group">
                    <label for="tuition">Max Tuition (per year)</label>
                    <select id="tuition">
                        <option value="">Select Tuition Range</option>
                        <option value="10000">Under $10,000</option>
                        <option value="20000">Under $20,000</option>
                        <option value="30000">Under $30,000</option>
                        <option value="40000">Under $40,000</option>
                        <option value="50000">Under $50,000</option>
                        <option value="any">Any</option>
                    </select>
                </div>
                
                <div class="filter-group">
                    <label for="size">College Size</label>
                    <select id="size">
                        <option value="">Select Size</option>
                        <option value="small">Small (Under 5,000)</option>
                        <option value="medium">Medium (5,000-15,000)</option>
                        <option value="large">Large (15,000+)</option>
                    </select>
                </div>
                
                <div class="filter-group">
                    <label for="type">Institution Type</label>
                    <select id="type">
                        <option value="">Select Type</option>
                        <option value="public">Public</option>
                        <option value="private">Private</option>
                        <option value="community">Community College</option>
                    </select>
                </div>
                
                <div class="filter-group">
                    <label for="rank">Minimum Ranking</label>
                    <select id="rank">
                        <option value="">Select Ranking</option>
                        <option value="100">Top 100</option>
                        <option value="200">Top 200</option>
                        <option value="300">Top 300</option>
                        <option value="any">Any</option>
                    </select>
                </div>
            </div>
            
            <button id="search-btn">Find Colleges</button>
        </section>
        
        <section class="results-section">
            <h2>Results</h2>
            <div id="results-container">
                <!-- College cards will be dynamically inserted here -->
                <div class="college-card">
                    <div class="college-header">
                        <h3>Massachusetts Institute of Technology (MIT)</h3>
                        <span class="match">95% Match</span>
                    </div>
                    <div class="college-body">
                        <div class="college-stats">
                            <div class="stat">
                                <div class="stat-label">Acceptance Rate</div>
                                <div class="stat-value">7%</div>
                            </div>
                            <div class="stat">
                                <div class="stat-label">Tuition</div>
                                <div class="stat-value">$55,450</div>
                            </div>
                            <div class="stat">
                                <div class="stat-label">Enrollment</div>
                                <div class="stat-value">11,520</div>
                            </div>
                            <div class="stat">
                                <div class="stat-label">Ranking</div>
                                <div class="stat-value">#2</div>
                            </div>
                        </div>
                        
                        <div class="college-courses">
                            <h4>Popular Courses</h4>
                            <div class="course-tags">
                                <span class="course-tag">Computer Science</span>
                                <span class="course-tag">Engineering</span>
                                <span class="course-tag">Mathematics</span>
                                <span class="course-tag">Physics</span>
                                <span class="course-tag">Economics</span>
                            </div>
                        </div>
                        
                        <p>MIT is a world-class educational institution with a mission to advance knowledge and educate students in science, technology, and other areas of scholarship.</p>
                        
                        <div class="college-actions">
                            <button onclick="showCollegeDetails('mit')">View Details</button>
                            <button class="save-btn">Save to Favorites</button>
                        </div>
                    </div>
                </div>
                
                <div class="college-card">
                    <div class="college-header">
                        <h3>Stanford University</h3>
                        <span class="match">92% Match</span>
                    </div>
                    <div class="college-body">
                        <div class="college-stats">
                            <div class="stat">
                                <div class="stat-label">Acceptance Rate</div>
                                <div class="stat-value">5%</div>
                            </div>
                            <div class="stat">
                                <div class="stat-label">Tuition</div>
                                <div class="stat-value">$56,169</div>
                            </div>
                            <div class="stat">
                                <div class="stat-label">Enrollment</div>
                                <div class="stat-value">17,249</div>
                            </div>
                            <div class="stat">
                                <div class="stat-label">Ranking</div>
                                <div class="stat-value">#3</div>
                            </div>
                        </div>
                        
                        <div class="college-courses">
                            <h4>Popular Courses</h4>
                            <div class="course-tags">
                                <span class="course-tag">Computer Science</span>
                                <span class="course-tag">Engineering</span>
                                <span class="course-tag">Business</span>
                                <span class="course-tag">Psychology</span>
                                <span class="course-tag">Biology</span>
                            </div>
                        </div>
                        
                        <p>Stanford University is a private research university known for its academic strength, wealth, and proximity to Silicon Valley.</p>
                        
                        <div class="college-actions">
                            <button onclick="showCollegeDetails('stanford')">View Details</button>
                            <button class="save-btn">Save to Favorites</button>
                        </div>
                    </div>
                </div>
                
                <div class="college-card">
                    <div class="college-header">
                        <h3>Harvard University</h3>
                        <span class="match">90% Match</span>
                    </div>
                    <div class="college-body">
                        <div class="college-stats">
                            <div class="stat">
                                <div class="stat-label">Acceptance Rate</div>
                                <div class="stat-value">5%</div>
                            </div>
                            <div class="stat">
                                <div class="stat-label">Tuition</div>
                                <div class="stat-value">$54,768</div>
                            </div>
                            <div class="stat">
                                <div class="stat-label">Enrollment</div>
                                <div class="stat-value">20,050</div>
                            </div>
                            <div class="stat">
                                <div class="stat-label">Ranking</div>
                                <div class="stat-value">#1</div>
                            </div>
                        </div>
                        
                        <div class="college-courses">
                            <h4>Popular Courses</h4>
                            <div class="course-tags">
                                <span class="course-tag">Economics</span>
                                <span class="course-tag">Political Science</span>
                                <span class="course-tag">Computer Science</span>
                                <span class="course-tag">Biology</span>
                                <span class="course-tag">History</span>
                            </div>
                        </div>
                        
                        <p>Harvard University is a private Ivy League research university with a history, influence, and wealth that make it one of the world's most prestigious universities.</p>
                        
                        <div class="college-actions">
                            <button onclick="showCollegeDetails('harvard')">View Details</button>
                            <button class="save-btn">Save to Favorites</button>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <section class="featured-section">
            <h2>Featured Resources</h2>
            <div class="featured-cards">
                <div class="featured-card">
                    <div class="featured-card-img">
                        <span>Scholarships</span>
                    </div>
                    <div class="featured-card-body">
                        <h3>Scholarship Finder</h3>
                        <p>Discover scholarships that match your profile and interests. Find financial aid opportunities to help fund your education.</p>
                        <a href="#scholarships">Explore Scholarships →</a>
                    </div>
                </div>
                
                <div class="featured-card">
                    <div class="featured-card-img">
                        <span>Career Paths</span>
                    </div>
                    <div class="featured-card-body">
                        <h3>Career Explorer</h3>
                        <p>Explore potential career paths based on your interests and skills. See which majors lead to your dream job.</p>
                        <a href="#careers">Explore Careers →</a>
                    </div>
                </div>
                
                <div class="featured-card">
                    <div class="featured-card-img">
                        <span>Campus Life</span>
                    </div>
                    <div class="featured-card-body">
                        <h3>Campus Experience</h3>
                        <p>Get insights into campus life, housing options, student organizations, and extracurricular activities.</p>
                        <a href="#campus">Explore Campus Life →</a>
                    </div>
                </div>
            </div>
        </section>
        
        <section id="resources" class="resources-section">
            <h2>College Planning Resources</h2>
            <div class="resources-grid">
                <div class="resource-card">
                    <h3>Application Timeline</h3>
                    <p>Stay on track with our comprehensive application timeline. From test prep to submission deadlines.</p>
                    <a href="#timeline">View Timeline →</a>
                </div>
                
                <div class="resource-card">
                    <h3>Essay Writing Tips</h3>
                    <p>Get expert advice on crafting compelling college application essays that showcase your unique story.</p>
                    <a href="#essays">Read Tips →</a>
                </div>
                
                <div class="resource-card">
                    <h3>Financial Aid Guide</h3>
                    <p>Understand your financial aid options, including FAFSA, grants, loans, and work-study programs.</p>
                    <a href="#financial-aid">Learn More →</a>
                </div>
                
                <div class="resource-card">
                    <h3>College Visit Checklist</h3>
                    <p>Make the most of your college visits with our comprehensive checklist of questions to ask and things to observe.</p>
                    <a href="#visits">Get Checklist →</a>
                </div>
            </div>
        </section>
    </div>
    
    <!-- College Details Modal -->
    <div id="college-modal" class="modal">
        <div class="modal-content">
            <span class="close-btn" onclick="closeModal()">&times;</span>
            <div id="modal-content">
                <!-- College details will be inserted here -->
            </div>
        </div>
    </div>
    
    <footer>
        <div class="footer-content">
            <div class="footer-column">
                <h3>College Finder</h3>
                <ul>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#team">Our Team</a></li>
                    <li><a href="#testimonials">Success Stories</a></li>
                    <li><a href="#partners">Partners</a></li>
                </ul>
            </div>
            
            <div class="footer-column">
                <h3>Resources</h3>
                <ul>
                    <li><a href="#blog">Blog</a></li>
                    <li><a href="#guides">Guides</a></li>
                    <li><a href="#webinars">Webinars</a></li>
                    <li><a href="#faq">FAQ</a></li>
                </ul>
            </div>
            
            <div class="footer-column">
                <h3>Support</h3>
                <ul>
                    <li><a href="#contact">Contact Us</a></li>
                    <li><a href="#help">Help Center</a></li>
                    <li><a href="#feedback">Feedback</a></li>
                    <li><a href="#terms">Terms of Service</a></li>
                </ul>
            </div>
            
            <div class="footer-column">
                <h3>Connect</h3>
                <ul>
                    <li><a href="#facebook">Facebook</a></li>
                    <li><a href="#twitter">Twitter</a></li>
                    <li><a href="#instagram">Instagram</a></li>
                    <li><a href="#linkedin">LinkedIn</a></li>
                </ul>
            </div>
        </div>
        
        <div class="footer-bottom">
            <p>&copy; 2025 College Finder. All rights reserved.</p>
        </div>
    </footer>
    
    <script>
        // College data
        const colleges = {
            mit: {
                name: "Massachusetts Institute of Technology (MIT)",
                description: "MIT is a world-class educational institution with a mission to advance knowledge and educate students in science, technology, and other areas of scholarship. Locate
