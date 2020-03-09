<h1>Kubernetes Starter</h1>

<h2>Secrets</h2>

<ol>
    <li>
        <p>Create Secrets</p>
        <blockquote>kubectl apply -f secrets/secret-definition.yml</blockquote>
    </li>
    <li>
        <p>Get Secrets</p>
        <blockquote>
            kubectl get secret<br />
            kubectl get secret secret-name<br />
            kubectl get secret secret-name -o yaml
        </blockquote>
    </li>
</ol>
