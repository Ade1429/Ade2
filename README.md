
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salesforce Administrator Portfolio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts - Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* Light gray background */
            color: #334155; /* Dark slate text */
        }
        .gradient-bg {
            background: linear-gradient(to right, #4F46E5, #6366F1); /* Indigo gradient */
        }
        .skill-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .skill-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }
        .project-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header -->
    <header class="bg-white shadow-sm py-4 sticky top-0 z-50">
        <nav class="container mx-auto px-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-indigo-700 rounded-lg p-2 hover:bg-indigo-50 transition-colors">
                Hey! I'm Adeyinka Aderibigbe-Yusuf
            </a>
            <div class="hidden md:flex space-x-6">
                <a href="#about" class="text-gray-600 hover:text-indigo-700 font-medium transition-colors">About</a>
                <a href="#skills" class="text-gray-600 hover:text-indigo-700 font-medium transition-colors">Skills</a>
                <a href="#portfolio" class="text-gray-600 hover:text-indigo-700 font-medium transition-colors">Portfolio</a>
                <a href="#contact" class="text-gray-600 hover:text-indigo-700 font-medium transition-colors">Contact</a>
            </div>
            <!-- Mobile Menu Button (Hamburger) -->
            <button id="mobile-menu-button" class="md:hidden text-gray-600 hover:text-indigo-700 focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                </svg>
            </button>
        </nav>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white mt-2 shadow-lg rounded-b-lg">
            <a href="#about" class="block px-4 py-2 text-gray-700 hover:bg-gray-100 transition-colors">About</a>
            <a href="#skills" class="block px-4 py-2 text-gray-700 hover:bg-gray-100 transition-colors">Skills</a>
            <a href="#portfolio" class="block px-4 py-2 text-gray-700 hover:bg-gray-100 transition-colors">Portfolio</a>
            <a href="#contact" class="block px-4 py-2 text-gray-700 hover:bg-gray-100 transition-colors">Contact</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="hero" class="gradient-bg text-white py-20 md:py-32 text-center shadow-lg">
        <div class="container mx-auto px-4">
            <h1 class="text-4xl md:text-6xl font-extrabold mb-4 leading-tight">
                Senior Salesforce Administrator
            </h1>
            <p class="text-lg md:text-xl mb-8 max-w-2xl mx-auto opacity-90">
                Driving efficiency and innovation through expert Salesforce platform management, automation, and data optimization.
            </p>
            <a href="#portfolio" class="bg-white text-indigo-700 hover:bg-indigo-50 hover:text-indigo-800 font-bold py-3 px-8 rounded-full shadow-lg transition-all duration-300 transform hover:scale-105">
                View My Projects
            </a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 md:py-24 bg-white">
        <div class="container mx-auto px-4 max-w-4xl">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 text-gray-800">About Me</h2>
            <div class="flex flex-col md:flex-row items-center md:space-x-8">
                <div class="md:w-1/3 mb-8 md:mb-0">
                    <img src=https://imgur.com/a/afVPrXV>
                </div>
                <div class="md:w-2/3 text-lg leading-relaxed text-gray-700 text-center md:text-left">
                    <p class="mb-4">
                        Hello! I'm a dedicated and results-driven Senior Salesforce Administrator with extensive experience in optimizing business processes and maximizing the value of the Salesforce platform. My passion lies in transforming complex requirements into scalable and efficient solutions.
                    </p>
                    <p>
                        I excel at leveraging Salesforce to enhance user productivity, maintain data integrity, ensure robust security, and deliver insightful analytics. I am committed to continuous learning and staying ahead of the curve with the latest Salesforce innovations to drive success for any organization.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-16 md:py-24 bg-gray-50">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 text-gray-800">My Core Skills</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Skill 1 -->
                <div class="skill-card bg-white p-6 rounded-lg shadow-md border border-gray-200">
                    <h3 class="text-xl font-semibold mb-3 text-indigo-700">1. Automation & Process Optimization</h3>
                    <p class="text-gray-600">Expert in designing and implementing robust automation solutions using Flow, Process Builder, and Workflow Rules to streamline operations and enhance efficiency.</p>
                </div>
                <!-- Skill 2 -->
                <div class="skill-card bg-white p-6 rounded-lg shadow-md border border-gray-200">
                    <h3 class="text-xl font-semibold mb-3 text-indigo-700">2. Salesforce Platform Management</h3>
                    <p class="text-gray-600">Comprehensive administration including configuration, customization, user management, and ongoing maintenance to ensure optimal platform performance.</p>
                </div>
                <!-- Skill 3 -->
                <div class="skill-card bg-white p-6 rounded-lg shadow-md border border-gray-200">
                    <h3 class="text-xl font-semibold mb-3 text-indigo-700">3. Security and Access Control</h3>
                    <p class="text-gray-600">Proficient in managing profiles, permission sets, roles, sharing rules, and organization-wide defaults to maintain data security and compliance.</p>
                </div>
                <!-- Skill 4 -->
                <div class="skill-card bg-white p-6 rounded-lg shadow-md border border-gray-200">
                    <h3 class="text-xl font-semibold mb-3 text-indigo-700">4. Process Mapping & Optimization</h3>
                    <p class="text-gray-600">Skilled in analyzing existing business processes, identifying inefficiencies, and designing improved workflows within Salesforce.</p>
                </div>
                <!-- Skill 5 -->
                <div class="skill-card bg-white p-6 rounded-lg shadow-md border border-gray-200">
                    <h3 class="text-xl font-semibold mb-3 text-indigo-700">5. Salesforce Data Management</h3>
                    <p class="text-gray-600">Adept at data import/export, cleansing, deduplication, and ensuring data quality and integrity using various Salesforce tools.</p>
                </div>
                <!-- Skill 6 -->
                <div class="skill-card bg-white p-6 rounded-lg shadow-md border border-gray-200">
                    <h3 class="text-xl font-semibold mb-3 text-indigo-700">6. Integration</h3>
                    <p class="text-gray-600">Experience with integrating Salesforce with other systems using standard connectors and understanding of API capabilities.</p>
                </div>
                <!-- Skill 7 -->
                <div class="skill-card bg-white p-6 rounded-lg shadow-md border border-gray-200">
                    <h3 class="text-xl font-semibold mb-3 text-indigo-700">7. Reporting & Dashboards</h3>
                    <p class="text-gray-600">Creating insightful reports and dynamic dashboards to provide key stakeholders with actionable business intelligence.</p>
                </div>
                <!-- Skill 8 (Placeholder for Skill 8) -->
                <div class="skill-card bg-white p-6 rounded-lg shadow-md border border-gray-200">
                    <h3 class="text-xl font-semibold mb-3 text-indigo-700">8. User Training & Support</h3>
                    <p class="text-gray-600">Developing training materials and providing ongoing support to ensure user adoption and proficiency on the platform.</p>
                </div>
                <!-- Skill 9 (Placeholder for Skill 9) -->
                <div class="skill-card bg-white p-6 rounded-lg shadow-md border border-gray-200">
                    <h3 class="text-xl font-semibold mb-3 text-indigo-700">9. Change Management</h3>
                    <p class="text-gray-600">Facilitating smooth transitions for new Salesforce features and processes, ensuring minimal disruption and maximum adoption.</p>
                </div>
                <!-- Skill 10 -->
                <div class="skill-card bg-white p-6 rounded-lg shadow-md border border-gray-200">
                    <h3 class="text-xl font-semibold mb-3 text-indigo-700">10. Testing & Quality Assurance (UAT) & Deployment</h3>
                    <p class="text-gray-600">Conducting thorough testing, managing User Acceptance Testing (UAT), and deploying changes effectively using Change Sets or other deployment tools.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="py-16 md:py-24 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 text-gray-800">My Portfolio Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project 1 -->
                <div class="project-card bg-white rounded-lg shadow-md overflow-hidden border border-gray-200">
                    <img src="https://placehold.co/600x400/e0e7ff/4338ca?text=Project+Image+1" alt="Project 1" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2 text-indigo-700">Automated Lead Routing System</h3>
                        <p class="text-gray-600 text-sm mb-4">Designed and implemented a complex Salesforce Flow to automatically assign leads to sales representatives based on specific criteria, reducing manual effort by 70%.</p>
                        <a href="#" class="text-indigo-600 hover:text-indigo-800 font-medium text-sm">Learn More &rarr;</a>
                    </div>
                </div>
                <!-- Project 2 -->
                <div class="project-card bg-white rounded-lg shadow-md overflow-hidden border border-gray-200">
                    <img src="https://placehold.co/600x400/ffe4e6/dc2626?text=Project+Image+2" alt="Project 2" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2 text-indigo-700">Custom Object for Contract Management</h3>
                        <p class="text-gray-600 text-sm mb-4">Developed a custom object and related fields, page layouts, and reports for efficient tracking and management of customer contracts within Salesforce.</p>
                        <a href="#" class="text-indigo-600 hover:text-indigo-800 font-medium text-sm">Learn More &rarr;</a>
                    </div>
                </div>
                <!-- Project 3 -->
                <div class="project-card bg-white rounded-lg shadow-md overflow-hidden border border-gray-200">
                    <img src="https://placehold.co/600x400/dbeafe/2563eb?text=Project+Image+3" alt="Project 3" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2 text-indigo-700">Enhanced Sales Performance Dashboard</h3>
                        <p class="text-gray-600 text-sm mb-4">Created a comprehensive set of Salesforce reports and dashboards providing real-time insights into sales pipeline, forecasting, and team performance metrics.</p>
                        <a href="#" class="text-indigo-600 hover:text-indigo-800 font-medium text-sm">Learn More &rarr;</a>
                    </div>
                </div>
                <!-- Project 4 (Placeholder) -->
                <div class="project-card bg-white rounded-lg shadow-md overflow-hidden border border-gray-200">
                    <img src="https://placehold.co/600x400/e0e7ff/4338ca?text=Coming+Soon" alt="Project 4" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2 text-indigo-700">Future Project Idea 1</h3>
                        <p class="text-gray-600 text-sm mb-4">Brief description of your next exciting Salesforce project. This could be anything from a new integration to a security hardening initiative.</p>
                        <a href="#" class="text-indigo-600 hover:text-indigo-800 font-medium text-sm">Learn More &rarr;</a>
                    </div>
                </div>
                <!-- Project 5 (Placeholder) -->
                <div class="project-card bg-white rounded-lg shadow-md overflow-hidden border border-gray-200">
                    <img src="https://placehold.co/600x400/ffe4e6/dc2626?text=Coming+Soon" alt="Project 5" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2 text-indigo-700">Future Project Idea 2</h3>
                        <p class="text-gray-600 text-sm mb-4">Another idea for a project you plan to add, showcasing your diverse skills and future contributions.</p>
                        <a href="#" class="text-indigo-600 hover:text-indigo-800 font-medium text-sm">Learn More &rarr;</a>
                    </div>
                </div>
                <!-- Project 6 (Placeholder) -->
                <div class="project-card bg-white rounded-lg shadow-md overflow-hidden border border-gray-200">
                    <img src="https://placehold.co/600x400/dbeafe/2563eb?text=Coming+Soon" alt="Project 6" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2 text-indigo-700">Future Project Idea 3</h3>
                        <p class="text-gray-600 text-sm mb-4">A third placeholder for an upcoming project, demonstrating your ongoing work and continuous improvement.</p>
                        <a href="#" class="text-indigo-600 hover:text-indigo-800 font-medium text-sm">Learn More &rarr;</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 md:py-24 bg-gray-50">
        <div class="container mx-auto px-4 max-w-2xl">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 text-gray-800">Get in Touch</h2>
            <div class="bg-white p-8 rounded-lg shadow-md border border-gray-200">
                <p class="text-gray-700 text-lg text-center mb-8">
                    Interested in collaborating or have a question? Feel free to reach out!
                </p>
                <form class="space-y-6">
                    <div>
                        <label for="name" class="block text-sm font-medium text-gray-700 mb-1">Name</label>
                        <input type="text" id="name" name="name" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm">
                    </div>
                    <div>
                        <label for="email" class="block text-sm font-medium text-gray-700 mb-1">Email</label>
                        <input type="email" id="email" name="email" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm">
                    </div>
                    <div>
                        <label for="message" class="block text-sm font-medium text-gray-700 mb-1">Message</label>
                        <textarea id="message" name="message" rows="5" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm"></textarea>
                    </div>
                    <div class="text-center">
                        <button type="submit" class="inline-flex justify-center py-3 px-8 border border-transparent shadow-sm text-base font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500 transition-colors duration-300">
                            Send Message
                        </button>
                    </div>
                </form>
                <div class="text-center mt-8 text-gray-600 text-sm">
                    <p>Or connect with me on:</p>
                    <div class="flex justify-center space-x-4 mt-2">
                        <a href="https://linkedin.com/in/yourprofile" target="_blank" class="text-indigo-600 hover:text-indigo-800 transition-colors">LinkedIn</a>
                        <a href="mailto:youremail@example.com" class="text-indigo-600 hover:text-indigo-800 transition-colors">Email</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8 text-center">
        <div class="container mx-auto px-4">
            <p>&copy; 2025 [Your Name]. All rights reserved.</p>
            <p class="text-sm mt-2">Built with <a href="https://tailwindcss.com/" target="_blank" class="text-indigo-400 hover:underline">Tailwind CSS</a></p>
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();

                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });

                // Close mobile menu if open
                if (mobileMenu.classList.contains('block')) {
                    mobileMenu.classList.remove('block');
                    mobileMenu.classList.add('hidden');
                }
            });
        });

        // Mobile menu toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
            mobileMenu.classList.toggle('block');
        });
    </script>

</body>
</html>

