# Image-Sender
The Image Sender project simplifies sending emails with attachments, offering a convenient communication solution. Users can compose emails, attach images, and send them seamlessly. The system ensures reliable email delivery and provides status updates, enhancing the user experience.
<h2>Installation Instructions:</h2>
    <ol>
        <li>Ensure you have the following prerequisites installed:
            <ul>
                <li>.NET Framework (version 7.0 or above)</li>
                <li>Visual Studio IDE (or any other .NET development environment)</li>
                <li>MySQL Server (or any other relational database management system)</li>
            </ul>
        </li>
        <li>Clone or download the Image Sender project repository from the provided source.</li>
        <li>Open the project solution file in Visual Studio.</li>
        <li>Restore the NuGet packages for the solution.</li>
        <li>Modify the database connection string as well as the Recipient Mail Adress, the folder path in the <code>appsettings.json</code> file to point to your MySQL Server instance.</li>
        <li>Modify Client ID and Secret in the <code>GmailServiceHelper.cs</code> class.</li>
        <li>Open Package Manager Console and run the migration commands to create the database schema:
            <pre><code>Update-Database</code></pre>
        </li>
    </ol>
