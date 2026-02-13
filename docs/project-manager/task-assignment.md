
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
                    <a href="../project-manager/charts.md" style="color: #ac9e9e; font-weight: bold; text-decoration: none;">Task Assignment</a>
                </div>   
                <div style="margin: 20px 0; text-align: center; border: 1px dashed #ccc; padding: 15px;">
                    <img src="../../assets/task-assigns.png">          
                </div>
                <h2 style="margin-top: 0;">Task Assignment (FR 6.1)</h2>
                <p>The Task Assignment module allows Project Managers to create, distribute, and manage project-related tasks among VSU SSC members to ensure organized execution of project activities. It records task details such as title, description, assigned member, deadline, and completion status to maintain accountability and clear responsibility tracking.<br>In its initial implementation, the module will support (1)manual task creation and assignment to specific members, (2)deadline setting with progress status indicators, and (3)task completion updates by assigned users. These features help Project Managers monitor workload distribution, track task progress in real time, and ensure timely completion of project deliverables.</p>   
                <h3>Use Case Scenario</h3>
                <table border="1" width="100%" cellpadding="8" cellspacing="0" style="border-collapse: collapse; font-size: 0.9em; border: 1px solid #ddd;">
                    <tr>
                        <th width="30%" align="left">Actor(s)</th>
                        <td>Project Manager, Lead Developer</td>
                    </tr>
                    <tr>
                        <th align="left">Goal</th>
                        <td>To assign, manage, and track projects tasks to ensure timely completion of project activities.</td>
                    </tr>
                    <tr>
                        <th align="left">Preconditions</th>
                        <td>
                            1. The project Manager is successfully authenticated in the system.<br>
                            2. A project already exists and is accessible.<br>
                            3. The project Manager has permission to assign tasks.
                        </td>
                    </tr>
                    <tr>
                        <th align="left">Main Scenario</th>
                        <td>
                            1. The PM selects a specific project from the dashboard.<br>
                            2. The PM opens the Task Assignment module.<br>
                            3. The system displays list of existing tasks.<br>
                            4. The PM creates or edits a task and assigns it to a member with a deadline.<br>
                            5. The PM saves the task details and stores the task information.<br>
                            6. The updated task list status are displayed in real time. 
                        </td>
                    </tr>
                    <tr>
                        <th align="left">Outcome</th>
                        <td> The tasks are successfully created or updated, and their assignments, deadlines, and completion statuses are saved and visible to authorized users.</td>
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
