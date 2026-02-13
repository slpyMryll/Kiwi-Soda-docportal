

<div>
    <table width="100%" cellpadding="10" cellspacing="0" style="font-family: Arial, sans-serif; border-collapse: collapse;">
        <tr>
            <td colspan="2" style="padding-bottom: 20px;">
                <h1 style="margin: 0;">Kiwi Soda</h1>
                <p style="font-weight: lighter; margin: 0;">Target: `KS.010.001`</p>
            </td>
        </tr>
        <tr>
            <td width="25%" valign="top" style="border: 1px solid #e0e0e0; border-right: none;">
                <h2 style="margin-top: 0;">Site Map</h2>  
                <a href="/docs/viewer/project-homepage.md">Homepage</a>           
                <p><strong>1. Authentication & Identity</strong></p>
                <ul style="list-style-type: none; padding-left: 0; font-size: 0.9em;">
                    <li style="padding-left: 15px"> <a href="../auth/google-login.md"> Login with Google (FR 1.0) </a></li>
                </ul>
                <p><strong>2. Student Viewer Hub</strong></p>
                <ul style="list-style-type: none; padding-left: 0; font-size: 0.9em;">
                    <li style="padding-left: 15px"> <a href="../viewer/dashboard.md"> Real-Time Dashboard (FR 2.0) </a></li>
                    <li style="padding-left: 15px"> <a href="../viewer/milestones.md"> Milestone Tracker (FR 2.1) </a></li>
                    <li style="padding-left: 15px"> <a href="../viewer/project-updates-hub.md"> Project Updates Hub (FR 3.0) </a></li>
                    <li style="padding-left: 15px"> <a href="../viewer/feedback.md"> Submit Feedback/Comments (FR 4.0) </a></li>
                    <li style="padding-left: 15px"> <a href="../viewer/chatbot.md"> FAQ Chatbot (FR 4.1) </a></li>
                    <li style="padding-left: 15px"> <a href="../viewer/project-follow-updates.md"> Project Follow Updates (FR 5.0) </a></li>
                    <li style="padding-left: 15px"> <a href="../viewer/subscription-notifier.md"> Subscription Notifier (FR 5.1) </a></li>
                </ul>
                <p><strong>3. Officer Management Portal</strong></p>
                <ul style="list-style-type: none; padding-left: 0; font-size: 0.9em;">
                    <li style="padding-left: 15px"> <a href="../project-manager/manage-projects.md"> Project Manager (FR 6.0) </a></li>
                    <li style="padding-left: 15px"> <a href="../project-manager/tasks.md"> Task Assignment (FR 6.1) </a></li>
                    <li style="padding-left: 15px"> <a href="../project-manager/timeline-monitor.md"> Timeline Monitor (FR 7.0) </a></li>
                    <li style="padding-left: 15px"> <a href="../project-manager/budget-tracker.md"> Budget Editor & Tracker (FR 8.0/8.1) </a></li>
                    <li style="padding-left: 15px"><a href="../project-manager/document-hub.md"> Document Hub (FR 9.0) </a></li>
                    <li style="padding-left: 15px"><a href="../project-manager/project-charts.md"> Progress Charts (FR 10.0) </a></li>
                    <li style="padding-left: 15px"> <a href="../project-manager/deadline-alerts.md"> Deadline Alerts (FR 11.0) </a></li>
                </ul>
                <p><strong>4. Admin & System Control</strong></p>
                <ul style="list-style-type: none; padding-left: 0; font-size: 0.9em;">
                    <li style="padding-left: 15px"> <a href="../admin/users.md"> User Role Management </a></li>
                    <li style="padding-left: 15px"> <a href="../admin/logs.md"> System Activity Logs </a></li>
                    <li style="padding-left: 15px"> <a href="../admin/settings.md"> Global Configuration </a></li>
                </ul>
            </td>
            <td valign="top" style="border: 1px solid #e0e0e0; padding: 20px;">
                <div style="margin-bottom: 15px; font-size: 0.85em; color: #666;">
                    <a href="../project-manager/" style=" text-decoration: none;">Projects</a> > 
                    <a href="../project-manager/charts.md" style="color: #ac9e9e; font-weight: bold; text-decoration: none;">Project Manager</a>
                </div>   
                <div style="margin: 20px 0; text-align: center; border: 1px dashed #ccc; padding: 15px;">
                    <img src="../../assets/project-management.png">          
                </div>
                <h2 style="margin-top: 0;">Project Manager (FR 6.0)</h2>
                <p>The Project Manager module enables authorized VSU SSC officers to create, organize, and oversee project activities within the system. It provides tools for managing timelines, assigning tasks, monitoring progress, handling budgets, and maintaining project documentation to ensure effective project execution.<br>In its initial implementation, the module will support (1)project creation and editing, (2)task assignment and deadline management, and (3)progress and budget monitoring. These capabilities allow Project Managers to coordinate project operations efficiently and ensure timely completion of planned activities.</h3>
                <table border="1" width="100%" cellpadding="8" cellspacing="0" style="border-collapse: collapse; font-size: 0.9em; border: 1px solid #ddd;">
                    <tr>
                        <th width="30%" align="left">Actor(s)</th>
                        <td>Project Manager, Lead Developer</td>
                    </tr>
                    <tr>
                        <th align="left">Goal</th>
                        <td>To allow Project Managers to manage and monitor all project activities to ensure successful and timely project completion.</td>
                    </tr>
                    <tr>
                        <th align="left">Preconditions</th>
                        <td>
                            1. The PM is authenticated in the system.<br>
                            2. The PM has the required permissions to manage projects.
                        </td>
                    </tr>
                    <tr>
                        <th align="left">Main Scenario</th>
                        <td>
                            1. The PM logs into the system.<br>
                            2. The PM creates or selects an existing project.<br>
                            3. The Project Manager manages tasks, timelines, budgets, and documents.<br>
                            4. The system saves and updates all project information and updates the status in real time.
                        </td>
                    </tr>
                    <tr>
                        <th align="left">Outcome</th>
                        <td> Project information is successfully created or updated, and all project activities are accurately tracked and accessible to authorized users.</td>
                    </tr>
                </table>
            </td>
        </tr>
        <tr>
            <td colspan="2" align="center" style="padding-top: 30px; font-size: 0.8em; color: #999;">
                <hr style="border: 0; border-top: 1px solid #eee; margin-bottom: 10px;">
                © 2026 Kinetix | OnTrack VSU SSC
            </td>
        </tr>
    </table>
</div>
