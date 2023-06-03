## Prompt engineering using `kubectl-ai` plugin

<table>
    <thead>
        <tr style="font-weight: bold; text-align: center">
            <td>NAME</td>
            <td>PROMPT</td>
            <td>DESCRIPTION</td>
            <td>EXAMPLE</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>nginx-deployment</td>
            <td><code>create deploy nginx</code></td>
            <td>Deployment based on Nginx server Docker image</td>
            <td><a href="/yaml/app.yaml">app.yaml</a></td>
        </tr>
        <tr>
            <td>liveness-probe</td>
            <td><code>create liveness probe every 30 seconds for nginx</code></td>
            <td>Liveness probe pod on Nginx server every 30 seconds</td>
            <td><a href="/yaml/app-livenessProbe.yaml">app-livenessProbe.yaml</a></td>
        </tr>
        <tr>
            <td>readiness-probe</td>
            <td><code>create readiness probe</code></td>
            <td>Readiness probe every 10 seconds</td>
            <td><a href="/yaml/app-readinessProbe.yaml">app-readinessProbe.yaml</a></td>
        </tr>
        <tr>
            <td>volume-mounts</td>
            <td><code>create container with mount volume</code></td>
            <td>Example of mounting volume in Nginx container</td>
            <td><a href="/yaml/app-volumeMounts.yaml">app-volumeMounts.yaml</a></td>
        </tr>
        <tr>
            <td>cronjob-pod</td>
            <td><code>create cron job running daily at 7 AM rebooting ubuntu</code></td>
            <td>Cronjob is being run daily at 7AM and reboot Ubuntu OS</td>
            <td><a href="/yaml/app-cronjob.yaml">app-cronjob.yaml</a></td>
        </tr>
        <tr>
            <td>job-pod</td>
            <td><code>create job syncing photos from google drive to local ubuntu</code></td>
            <td>Job syncing Google drive files to Ubuntu machine</td>
            <td><a href="/yaml/app-job.yaml">app-job.yaml</a></td>
        </tr>
        <tr>
            <td>multicontainer-pod</td>
            <td><code>create multicontainer pod nginx with ubuntu and common volume</code></td>
            <td>Pod contained 2 containers (Ubuntu and Nginx) and volume</td>
            <td><a href="/yaml/app-multicontainer.yaml">app-multicontainer.yaml</a></td>
        </tr>
        <tr>
            <td>resources-pod</td>
            <td><code>create manifest with cpu and memory resources</code></td>
            <td>Pod with limitation of CPU and memory usage</td>
            <td><a href="/yaml/app-resources.yaml">app-resources.yaml</a></td>
        </tr>
        <tr>
            <td>secret-env-pod</td>
            <td><code>"create secret environment for mysql</code></td>
            <td>Secret pod with random credentials for MySQL database</td>
            <td><a href="/yaml/app-secret-env.yaml">app-secret-env.yaml</a></td>
        </tr>
    </tbody>
</table>