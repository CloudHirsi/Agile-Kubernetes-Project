# Agile Kubernetes Project
## ***Kubernetes Management and Maintenance + Agile Methodologies***

## **Overview:**
This project showcases my expertise in managing and maintaining Kubernetes clusters, utilizing Agile methodologies and Scrum principles to ensure efficient project management and delivery. By leveraging Jira for project management, I effectively organized and tracked the progress of various tasks, ranging from cluster upgrades and backups to application scaling. The successful implementation of these tasks highlights my proficiency in both Kubernetes administration and Agile project management.

![image](https://github.com/CloudHirsi/Agile-Kubernetes-Project/assets/153539293/9c72397d-4f50-4d23-8140-af5f58774c42)
![image](https://github.com/CloudHirsi/Agile-Kubernetes-Project/assets/153539293/c8092ced-24a3-4252-9183-1736d1d99ca1)

## **Key Agile Practices Implemented:**
- Sprint Planning: Defined sprint goals and planned tasks for each sprint to ensure focused and achievable objectives.
- Sprint Reviews: Reviewed work done and sprint goals.

![image](https://github.com/CloudHirsi/Agile-Kubernetes-Project/assets/153539293/df4b63a3-0d7f-45a2-a00d-f6d3ccf34d6b)

## **Tasks:**
1. Upgrading Kubernetes Cluster
Task: Upgraded both the master and worker nodes of the Kubernetes cluster.
Approach: Planned and executed the upgrade in a controlled manner to minimize downtime and ensure smooth transitions.
Outcome: Successfully upgraded the cluster with minimal disruption to running applications, enhancing cluster performance and security.

**Master Node:**

- ControlPlane:

![image](https://github.com/CloudHirsi/Agile-Kubernetes-Project/assets/153539293/21020da6-3c2c-4cef-93ae-1f297272ece4)
![image](https://github.com/CloudHirsi/Agile-Kubernetes-Project/assets/153539293/cf8442a0-5de4-41ad-b63b-8807df56c377)
- Kubelet:

![image](https://github.com/CloudHirsi/Agile-Kubernetes-Project/assets/153539293/62a193a8-4804-40bd-8fdf-ebfadbc2e45e)

**Worker Node:**

![image](https://github.com/CloudHirsi/Agile-Kubernetes-Project/assets/153539293/cbaeeb8d-8869-4a32-8a74-2d0697cd2438)

2. Taking Snapshot of ETCD
Task: Created a snapshot of the ETCD database before the regular maintenance reboot.
Approach: Documented and executed the snapshot process to ensure data consistency and availability.
Outcome: Successfully captured the state of the ETCD database, enabling reliable recovery in case of issues during maintenance.

![image](https://github.com/CloudHirsi/Agile-Kubernetes-Project/assets/153539293/cb07c118-9fb6-440d-b2fc-8166980e8b72)

3. Restoring ETCD Snapshot to Fix Application Issue
Task: Fixed an issue where the application was no longer accessible by restoring the ETCD snapshot taken earlier.
Approach: Identified the root cause of the issue and used the snapshot to restore the application state.
Outcome: Restored application accessibility promptly, demonstrating effective use of backups for disaster recovery.

![image](https://github.com/CloudHirsi/Agile-Kubernetes-Project/assets/153539293/3511f570-5c46-4eb3-ae0e-33dc74663e34)

4. Creating PersistentVolume and PersistentVolumeClaim and Mounting to a Po
Task: Created PersistentVolume (PV) and PersistentVolumeClaim (PVC) to mount to the application through the pod definition YAML file.
Approach: Designed and implemented PV and PVC configurations to ensure persistent storage for the application.
Outcome: Successfully deployed the application with persistent storage, ensuring data durability and resilience.

![image](https://github.com/CloudHirsi/Agile-Kubernetes-Project/assets/153539293/482d54e7-624e-43a3-bd85-25de5db80b51)
![image](https://github.com/CloudHirsi/Agile-Kubernetes-Project/assets/153539293/3e6fd027-915b-4fa4-8397-ecf0f4bdb447)

7. Scaling the Application
Task: Scaled the application by adjusting the deployment configuration.
Approach: Modified the deployment YAML file to increase the number of replicas, ensuring the application could handle increased load.
Outcome: Efficiently scaled the application, improving its availability and performance under high traffic conditions.

![image](https://github.com/CloudHirsi/Agile-Kubernetes-Project/assets/153539293/5932eb96-b059-4102-9318-d162f2a8b45e)

## **Conclusion**
This project not only demonstrates my technical skills in managing Kubernetes clusters but also highlights my ability to apply Agile methodologies to ensure efficient project delivery. By leveraging Jira for project management, I maintained clear visibility into task progress and ensured continuous improvement throughout the project lifecycle. This experience has equipped me with the skills to manage complex projects and deliver high-quality results in a dynamic and agile environment.




