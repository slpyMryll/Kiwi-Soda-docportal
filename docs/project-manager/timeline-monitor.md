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
                    <a href="../project-manager/charts.md" style="color: #ac9e9e; font-weight: bold; text-decoration: none;">Timeline Monitor</a>
                </div>   
                <div style="margin: 20px 0; text-align: center; border: 1px dashed #ccc; padding: 15px;">
                    <img src="../../assets/project-monitor.png">          
                </div>
                <h2 style="margin-top: 0;">Timeline Monitor (FR 7.0)</h2>
                <p>The Timeline Monitor module enables Project Managers to plan, track, and update the chrnological progress of VSY SSC projects through an organized timeline view. It consolidates milestone, task deadlines, and deliverable schedules into a single interface to support accurate project monitoring and timely completion.<br>In its initial implementation, the module will provide (1)timeline creation wth defined milestones and target dates, (2) real-time progress updates based on task completion status, and (3)visual indicators for Proposed, Approved, In-execution, and Completed activities. These features allow Project Managers to easily assess project status, identify scheduling risks, and maintain alignment with planned project timelines.</p>   
                <h3>Use Case Scenario</h3>
                <table border="1" width="100%" cellpadding="8" cellspacing="0" style="border-collapse: collapse; font-size: 0.9em; border: 1px solid #ddd;">
                    <tr>
                        <th width="30%" align="left">Actor(s)</th>
                        <td>Project Manager, Lead Developer</td>
                    </tr>
                    <tr>
                        <th align="left">Goal</th>
                        <td>To track and manage project milestones, deadlines, and progress to ensure timely projet completion.</td>
                    </tr>
                    <tr>
                        <th align="left">Preconditions</th>
                        <td>
                            1. The project Manager is successfully authenticated in the system.<br>
                            2. A project has already been created and is accessible to the Project Manager.<br>
                            3. The project Manager has permission to view and modify the project timeline.
                        </td>
                    </tr>
                    <tr>
                        <th align="left">Main Scenario</th>
                        <td>
                            1. The PM selects a specific project from the dashboard.<br>
                            2. The PM opens the Timeline Monitor module.<br>
                            3. The system displays the current milestone, deadlines, and progress indicators.<br>
                            4. The PM adds or edits milestones and target dates as needed.<br>
                            5. The PM saves the updated timeline.<br>
                            6. The System validates and stores the changes. <br>
                            7. The updated timeline and progess status are displayed in real time. 
                        </td>
                    </tr>
                    <tr>
                        <th align="left">Outcome</th>
                        <td> The project timeline is successfully created or updated, and the latest milestones, deadlines, and progress status are saved and displayed to authorized users in real time.</td>
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
