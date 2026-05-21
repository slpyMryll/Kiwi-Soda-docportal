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
                    <a href="../admin/" style=" text-decoration: none;">Admin</a> &gt; 
                    <a href="/docs/admin/settings.md" style="color: #ac9e9e; font-weight: bold; text-decoration: none;">Global Configuration</a>
                </div>           
                <div style="margin: 20px 0; text-align: center; border: 1px dashed #ccc; padding: 15px;">
                    <img src="../../assets/ontrack_global-configuration.png">
                </div>
                <h2 style="margin-top: 0;">Global Configuration</h2>
                <p>The Global Configuration feature allows administrators to manage system-wide settings that control the overall behavior of the OnTrack platform. It defines default configurations such as system preferences, notification rules, and feature toggles.
                </p>
                <p>This feature ensures consistency and flexibility across the system by allowing  administrators to adjust global parameters without modifying individual modules. It helps maintain centralized control over how the platform operates for all users, including Admins, Project Managers, and Viewers.</p>
                <h3>Use Case Scenario</h3>
                <table border="1" width="100%" cellpadding="8" cellspacing="0" style="border-collapse: collapse; font-size: 0.9em; border: 1px solid #ddd;">
                    <tr>
                        <th width="30%" align="left">Actor(s)</th>
                        <td>Administrator</td>
                    </tr>
                    <tr>
                        <th align="left">Goal</th>
                        <td>To configure and manage system-wide settings that affect the behavior of the entire OnTrack platform.</td>
                    </tr>
                    <tr>
                        <th align="left">Preconditions</th>
                        <td>
                            1. Administrator must be logged into the OnTrack system.<br>
                            2.  Platform configuration module must be enabled.
                        </td>
                    </tr>
                    <tr>
                        <th align="left">Main Scenario</th>
                         <td>
                            1. Administrator opens the Platform Settings module.<br>
                            2. The system displays all global configuration options.<br>
                            3. Administrator updates settings such as notifications, defaults, or feature toggles.<br>
                            4. The system validates the changes to ensure compatibility.<br>
                            5. Administrator saves the updated configuration.<br>
                            6. The system applies the new settings across all affected modules.
                        </td>
                    </tr>
                    <tr>
                        <th align="left">Outcome</th>
                        <td> System-wide settings are successfully updated and applied,
                            ensuring consistent behavior across the OnTrack platform.</td>
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