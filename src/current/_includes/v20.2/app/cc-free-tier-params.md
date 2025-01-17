Where:

- `{username}` and `{password}` specify the SQL username and password that you created earlier.
- `{globalhost}` is the name of the CockroachDB {{ site.data.products.serverless }} host (e.g., `free-tier.gcp-us-central1.cockroachlabs.cloud`).
- `{path to the CA certificate}` is the path to the `cc-ca.crt` file that you downloaded from the CockroachDB {{ site.data.products.cloud }} Console.
- `{cluster_name}` is the name of your cluster.

{{site.data.alerts.callout_info}}
If you are using the connection string that you [copied from the **Connection info** dialog](#set-up-your-cluster-connection), your username, password, hostname, and cluster name will be pre-populated.
{{site.data.alerts.end}}
