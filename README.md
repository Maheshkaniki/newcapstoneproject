# newcapstoneproject
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WebsiteOn Dashboard</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <div class="dashboard">
        <header class="header">
            <div class="logo"><i class="fas fa-chart-line"></i> WebsiteOn</div>
            <nav class="nav">
                <a href="#"><i class="fas fa-home"></i> Overview</a>
                <a href="#"><i class="fas fa-tachometer-alt"></i> Performance</a>
                <a href="#"><i class="fas fa-shield-alt"></i> Security</a>
                <a href="#"><i class="fas fa-chart-bar"></i> Analytics</a>
                <a href="#"><i class="fas fa-lightbulb"></i> Insights</a>
                <a href="#"><i class="fas fa-cogs"></i> Settings</a>
            </nav>
            <div class="user-profile"><i class="fas fa-user"></i> User Profile</div>
        </header>

        <section class="overview">
            <div class="real-time-alerts">
                <h2><i class="fas fa-bell"></i> Real-time Alerts</h2>
                <ul>
                    <li>Server downtime at 2:00 PM</li>
                    <li>New user registration at 3:30 PM</li>
                </ul>
            </div>
            <div class="kpis">
                <h2><i class="fas fa-chart-line"></i> Key Performance Indicators</h2>
                <p>Uptime: 99.9%</p>
                <p>Load Time: 1.2s</p>
                <p>Traffic: 5,000 visits/day</p>
            </div>
            <div class="website-health">
                <h2><i class="fas fa-heartbeat"></i> Website Health Status</h2>
                <div class="progress-bar">
                    <div class="progress" style="width: 80%;"></div>
                </div>
                <p>Status: Good</p>
            </div>
        </section>

        <section class="performance">
            <h2><i class="fas fa-tachometer-alt"></i> Performance Monitoring</h2>
            <div class="performance-metrics">
                <div class="uptime-status">
                    <h3>Uptime Status</h3>
                    <div class="gauge">99.9%</div>
                </div>
                <div class="response-time">
                    <h3>Server Response Time</h3>
                    <img src="response-time-graph.png" alt="Server Response Time">
                </div>
                <div class="load-time">
                    <h3>Load Time Statistics</h3>
                    <img src="load-time-chart.png" alt="Load Time Statistics">
                </div>
                <div class="traffic-analysis">
                    <h3>Traffic Analysis</h3>
                    <img src="traffic-pie-chart.png" alt="Traffic Analysis">
                </div>
            </div>
        </section>

        <section class="security">
            <h2><i class="fas fa-shield-alt"></i> Security Monitoring</h2>
            <div class="security-metrics">
                <div class="malware-detection">
                    <h3>Malware Detection</h3>
                    <p>Status: No threats detected</p>
                </div>
                <div class="blocklist-status">
                    <h3>Blocklist Status</h3>
                    <p>Checked: OK</p>
                </div>
                <div class="ssl-status">
                    <h3>SSL Certificate Status</h3>
                    <p>Valid until: 2025-12-31</p>
                </div>
                <div class="dns-configuration">
                    <h3>DNS Configuration</h3>
                    <p>Warnings: None</p>
                </div>
            </div>
        </section>

        <section class="analytics">
            <h2><i class="fas fa-chart-bar"></i> Analytics and Reports</h2>
            <div class="analytics-metrics">
                <div class="traffic-sources">
                    <h3>Traffic Sources</h3>
                    <img src="traffic-sources-bar-chart.png" alt="Traffic Sources">
                </div>
                <div class="user-behavior">
                    <h3>User Behavior</h3>
                    <img src="user-behavior-heatmap.png" alt="User Behavior">
                </div>
                <div class="page-performance">
                    <h3>Page Performance Insights</h3>
                    <p>Top Pages: Page 1, Page 2</p>
                </div>
                <div class="custom-reports">
                    <h3>Customizable Reports</h3>
                    <p>Generate and download reports</p>
                </div>
            </div>
        </section>

        <section class="insights">
            <h2><i class="fas fa-lightbulb"></i> Actionable Insights</h2>
            <div class="insights-metrics">
                <div class="performance-improvements">
                    <h3>Performance Improvements</h3>
                    <ul>
                        <li>Optimize images on Page 1</li>
                        <li>Minimize JavaScript on Page 2</li>
                    </ul>
                </div>
                <div class="security-enhancements">
                    <h3>Security Enhancements</h3>
                    <ul>
                        <li>Enable 2FA</li>
                        <li>Update CMS</li>
                    </ul>
                </div>
                <div class="historical-data">
                    <h3>Historical Data Comparison</h3>
                    <img src="historical-data-graph.png" alt="Historical Data">
                </div>
            </div>
        </section>

        <section class="user-settings">
            <h2><i class="fas fa-cogs"></i> User Settings</h2>
            <div class="settings-options">
                <div class="account-management">
                    <h3>Account Management</h3>
                    <p>Edit profile, change password</p>
                </div>
                <div class="notification-preferences">
                    <h3>Notification Preferences</h3>
                    <p>Manage notification settings</p>
                </div>
                <div class="custom-dashboard">
                    <h3>Customizable Dashboard Views</h3>
                    <p>Customize layout and sections</p>
                </div>
            </div>
        </section>
    </div>
</body>
</html>


body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

.dashboard {
    width: 90%;
    margin: 0 auto;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #333;
    color: #fff;
    padding: 10px 20px;
}

.header .logo {
    font-size: 24px;
    font-weight: bold;
}

.header .nav a {
    color: #fff;
    margin: 0 10px;
    text-decoration: none;
    display: flex;
    align-items: center;
}

.header .nav a:hover {
    text-decoration: underline;
}

.header .user-profile {
    cursor: pointer;
}

section {
    margin: 20px 0;
}

h2 {
    color: #333;
    border-bottom: 2px solid #333;
    padding-bottom: 10px;
    display: flex;
    align-items: center;
}

h2 i {
    margin-right: 10px;
}

.performance-metrics,
.security-metrics,
.analytics-metrics,
.insights-metrics,
.settings-options {
    display: flex;
    flex-wrap: wrap;
}

.performance-metrics > div,
.security-metrics > div,
.analytics-metrics > div,
.insights-metrics > div,
.settings-options > div {
    flex: 1 1 45%;
    margin: 10px;
    padding: 20px;
    background-color: #f9f9f9;
    border: 1px solid #ddd;
    border-radius: 5px;
}

.gauge {
    width: 100px;
    height: 100px;
    background-color: #4caf50;
    border-radius: 50%;
    color: #fff;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 24px;
    margin: 0 auto;
}

.progress-bar {
    width: 100%;
    background-color: #ddd;
    border-radius: 5px;
    overflow: hidden;
   Continuing with the CSS for your enhanced dashboard:

### Enhanced CSS (Continued)

```css
.progress {
    height: 20px;
    background-color: #4caf50;
}

img {
    width: 100%;
    height: auto;
    border: 1px solid #ddd;
    border-radius: 5px;
}

.real-time-alerts ul {
    list-style: none;
    padding: 0;
}

.real-time-alerts li {
    background: #f8d7da;
    color: #721c24;
    padding: 10px;
    margin: 5px 0;
    border-radius: 5px;
}

.kpis p {
    background: #d4edda;
    color: #155724;
    padding: 10px;
    margin: 5px 0;
    border-radius: 5px;
}

.header .nav a.active {
    font-weight: bold;
    border-bottom: 2px solid #fff;
}

@media (max-width: 768px) {
    .header {
        flex-direction: column;
    }

    .nav {
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .performance-metrics,
    .security-metrics,
    .analytics-metrics,
    .insights-metrics,
    .settings-options {
        flex-direction: column;
    }

    .performance-metrics > div,
    .security-metrics > div,
    .analytics-metrics > div,
    .insights-metrics > div,
    .settings-options > div {
        flex: 1 1 100%;
    }
}
