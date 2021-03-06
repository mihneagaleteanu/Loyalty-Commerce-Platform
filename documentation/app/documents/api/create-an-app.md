### Create an App

To create a new application, POST the application name and description to `/apps` and sign the request with your account credentials. Sandbox credentials are created automatically when you create an app. Your app can use these credentials to access the sandbox environment. Credentials to access the live environment can only be created by Points.

#### Parameters

<table>
    <thead>
        <tr>
            <th>Name</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>name</td>
            <td>The name of your app (required). Provide a short name for your app, up to 50 characters. Ensure that there is enough information available for Points to identify the owner and purpose of the app.</td>
        </tr>
        <tr>
            <td>description</td>
            <td>A description for your app (required). Provide a detailed description of your app, up to 4000 characters.</td>
        </tr>
    </tbody>
</table>

#### Returns

The app object if it was created successfully. Returns an [error](./?doc=reference-manual#errors) if the name or description is not provided.






