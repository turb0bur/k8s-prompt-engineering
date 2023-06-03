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
            <td><pre>create deploy nginx</pre></td>
            <td>Deployment based on Nginx server Docker image</td>
            <td><a href="/yaml/nginx-deployment.yaml">nginx-deployment</a></td>
        </tr>
        <tr>
            <td>liveness-probe</td>
            <td><pre>create liveness probe every 30 seconds for nginx</pre></td>
            <td>Liveness probe pod on Nginx server every 30 seconds</td>
            <td><a href="/yaml/nginx-liveness-probe.yaml">liveness-probe</a></td>
        </tr>
        <tr>
            <td>mysql-db</td>
            <td><pre>create mysql 8.0 with secrets as a credentianls</pre></td>
            <td>MySQL 8.0 database server with credentials in secret and persistent volume claim</td>
            <td><a href="/yaml/mysql-deployment.yaml">mysql-db</a></td>
        </tr>
        <tr>
            <td>multicontainer-pod</td>
            <td><pre>create multicontainer pod nginx with ubuntu and common volume</pre></td>
            <td>Pod contained 2 containers (Ubuntu and Nginx) and volume</td>
            <td><a href="/yaml/multicontainer-pod.yaml">milticontainer-pod</a></td>
        </tr>
        <tr>
            <td>cronjob-pod</td>
            <td><pre>"create cron job running daily at 7 AM rebootingubuntu</pre></td>
            <td>Cronjob is being run daily at 7AM and reboot Ubuntu OS</td>
            <td><a href="/yaml/cronjob-pod.yaml">cronjob-pod</a></td>
        </tr>
    </tbody>
</table>