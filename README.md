# HashiCorp Hackathon Project Proposal

## Classroom Training Deployments

### Team Members

John Dohoney, Tyler Walker, Gonzalo Lopez, Roger Chao

### Technologies

```Infrastructure:``` ie GCP, GKE, Terraform

```Service Configuration and Service Discovery:``` Consul

```Application:``` Front end portal + Showoff (OSS application) + Wetty

### Business Case

Delivering classroom technical training requires travel to and from locations. This can be costly and also often requires students to download software that often does not involve the solution being taught. Attempts at fixing this problem are often one off solutions that don’t repeatability scale and lead to poor learning experience. This is a problem for online colleges, companies and partners delivering training solutions. 
Description
Team 3 plans to build a classroom training experience that enables teacher to repeatedly deploy training environments. This will eliminate the complexity and allow them to focus on delivering quality training for the students. 

The training solution will have a frontend student sign-up and will integrate with Terraform to provision the classroom. This will include the training application itself, which will  be running on K8s and backed by a repo which will serve the content for the class. Additionally, wetty containers to forward SSH sessions via browser to VMs that will have the needed tooling for student exercises. All of the K8s services will be registered with Consul and will run health checks across the class environment.

###High-level Project Tasks

Showoff application and Frontend - `(Tyler Walker)`
Terraform provisioning of environment - `(Gonzalo Lopez)`
Consul Integration - `(John Dohoney / Roger Chao)`
Overall testing and integration - `( the team )`

