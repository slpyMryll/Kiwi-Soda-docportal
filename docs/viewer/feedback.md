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
                <p><strong>1. Authentication & Identity</strong></p>
                <ul style="list-style-type: none; padding-left: 0; font-size: 0.9em;">
                    <li style="padding-left: 15px"> <a href="../auth/homepage.md"> HomePage</a><li>
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
                    <a href="docs/viewer/" style=" text-decoration: none;">Viewer Hub</a> &gt; 
                    <a href="docs/viewer/updates.md" style="color: #ac9e9e; font-weight: bold; text-decoration: none;">Submit Feedback/Comments</a>
                </div>           
                <div style="margin: 20px 0; text-align: center; border: 1px dashed #ccc; padding: 15px;">
                    <img src="../../assets/feedback.png">
                </div>
                <h2 style="margin-top: 0;">Feedback Submitter (FR 4.0)</h2>
                <p>The Feedback Submitter allows users to provide comments, questions, and suggestions
                related to specific projects through an interactive form interface.
                It enables communication between viewers and project officers to improve transparency
                and project engagement.</p>
                <p>This feature supports structured feedback submission, allowing users to enter messages,
                attach relevant details, and submit inquiries regarding project updates, issues,
                or clarifications. Submitted feedback is stored and made accessible for review
                by authorized personnel.</p>
                <h3>Use Case Scenario</h3>
                <table border="1" width="100%" cellpadding="8" cellspacing="0" style="border-collapse: collapse; font-size: 0.9em; border: 1px solid #ddd;">
                    <tr>
                        <th width="30%" align="left">Actor(s)</th>
                        <td>Student Viewer</td>
                    </tr>
                    <tr>
                        <th align="left">Goal</th>
                        <td>To submit feedback, comments, or questions regarding a project.</td>
                    </tr>
                    <tr>
                        <th align="left">Preconditions</th>
                        <td>
                            1. User must be logged in.<br>
                            2. Project must be available for feedback submission.  </td>
                    </tr>
                    <tr>
                        <th align="left">Main Scenario</th>
                        <td>
                            1. User navigates to a project dashboard.<br>
                            2. User clicks the "Comments" button in a project card.<br>
                            3. System shows the comments section.<br>
                            4. User enters comments, questions, or suggestions.<br>
                            5. User submits the feedback.<br>
                            6. System stores the feedback and confirms submission.
                        </td>
                    </tr>
                    <tr>
                        <th align="left">Outcome</th>
                        <td>User feedback is successfully recorded and available for review by authorized users.</td>
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