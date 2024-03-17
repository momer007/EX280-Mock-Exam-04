# EX280-Mock-Exam-04
EX280-Mock-Exam-04

Performance-Based Exam: Comprehensive OpenShift Administration

Instructions:

This exam consists of practical tasks covering all objectives of OpenShift administration.
Ensure that all configurations persist after a cluster reboot without intervention.
You have 4 hours to complete the exam.
Utilize the provided environment, including the web console, command-line interface, and product documentation as needed.

Task 1: Cluster Management

	1.1. Easy: Create a new project named "cluster-management".

	1.2. Easy: List all projects in the cluster and their associated resource usage.

	1.3. Easy: Check the cluster-wide resource quotas and adjust them to accommodate future growth.

	1.4. Tough: Configure OAuth-based authentication for the OpenShift web console using an external identity provider (e.g., Keycloak).

	1.5. Tough: Implement network policies to restrict traffic between namespaces and enforce communication rules.

	1.6. Much Tougher: Integrate OpenShift with an external monitoring system (e.g., Prometheus) for comprehensive cluster monitoring.

Task 2: Application Deployment

	2.1. Easy: Deploy a simple "Hello World" application using the OpenShift web console.

	2.2. Easy: Scale the "Hello World" application to 3 replicas using the command-line interface.

	2.3. Easy: Expose the "Hello World" application externally using a route with TLS termination.

	2.4. Tough: Deploy a stateful application (e.g., Redis) with persistent storage and implement rolling updates without service downtime.

	2.5. Tough: Utilize the GitOps methodology to automate application deployments from a Git repository using ArgoCD.

	2.6. Much Tougher: Implement Blue-Green deployment strategy for a critical microservices-based application, ensuring zero-downtime deployments.

Task 3: Storage Management

	3.1. Easy: Create a new PersistentVolumeClaim (PVC) with ReadWriteMany access mode for shared storage usage.

	3.2. Easy: Attach the PVC to a running application pod and verify the storage mount.

	3.3. Easy: Resize an existing PersistentVolume (PV) dynamically to accommodate increased storage requirements.

	3.4. Tough: Implement data encryption-at-rest for all storage resources within the cluster.

	3.5. Tough: Set up automated backups for critical application data stored in PersistentVolumes, with scheduled retention policies.

	3.6. Much Tougher: Configure cross-cluster replication for disaster recovery purposes, ensuring data synchronization between geographically dispersed clusters.

Task 4: Application Scalability and Reliability

	4.1. Easy: Configure horizontal pod autoscaling for a sample application based on CPU utilization.

	4.2. Easy: Implement pod affinity rules to optimize resource utilization and performance.

	4.3. Easy: Set up a health check endpoint for an application and configure readiness probes to manage traffic during application startup.

	4.4. Tough: Implement advanced traffic splitting strategies (e.g., canary deployments) for gradual application rollouts.

	4.5. Tough: Configure Priority and Preemption policies to ensure high-priority workloads receive resources during resource contention.

	4.6. Much Tougher: Implement chaos engineering practices to proactively identify and mitigate potential failures within the cluster.

Task 5: Security and Compliance

	5.1. Easy: Create a new service account with limited permissions and assign it to a specific namespace.

	5.2. Easy: Enable Pod Security Policies (PSPs) to restrict privilege escalation and unauthorized access within pods.

	5.3. Easy: Rotate TLS certificates used for securing internal communication between OpenShift components.

	5.4. Tough: Implement PodSecurityContext to enforce specific security settings (e.g., runAsNonRoot, readOnlyRootFilesystem) for container processes.

	5.5. Tough: Integrate OpenShift with a third-party security solution (e.g., Falco) for real-time threat detection and response.

	5.6. Much Tougher: Implement end-to-end encryption for all intra-cluster communication using Istio Service Mesh.

Task 6: Monitoring and Logging

	6.1. Easy: Set up basic monitoring using Prometheus and visualize cluster metrics using Grafana dashboards.

	6.2. Easy: Configure log aggregation for all pods within a namespace using Elasticsearch and Kibana.

	6.3. Easy: Set up alerts for critical cluster events using built-in OpenShift alerting mechanisms.

	6.4. Tough: Implement custom Prometheus exporters to monitor application-specific metrics.

	6.5. Tough: Centralize audit logs for all administrative actions performed within the OpenShift cluster.

	6.6. Much Tougher: Implement distributed tracing using Jaeger for deep visibility into application performance and dependencies.
