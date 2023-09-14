List of oc subcommands:
adm - to administer an OpenShift cluster
annotate - update the annotations on a resource
api-resources - to view the list of supported API resources on the server
api-versions - to view the supported API versions in the form of "group/version"
apply - to apply a configuration to a resource by file name or by stdin
attach - to attach to a running container
auth - to check permissions;  to manage RBAC roles, role bindings, cluster roles, and cluster role binding objects
autoscale - to autoscale a deployment config, deployment, replica set, stateful set, or replication controller
cancel-build - to cancel running, pending, or new builds
cluster-info - to display cluster information
completion - output shell completion code for specified shells (bash, zsh, fish, or powershell)
config - to show or set various values in a kubeconfig file
cp - to copy files and directories to and from containers
create - to create a resource from a file or from stdin.   Has numerous subcommands for specific resources
debug - to launch a new instance of a pod for debugging
delete - to delete resources by file names, stdin, resources, and names or by resources and label selector.
describe - to show details of a specific resource or group of resources
diff - to diff a live version against a would-be applied version
edit - to edit a resource on the server
*events - to list events
exec - to execute a command in a container
explain - to view descriptions and fields for a particular resource:   oc explain pods
expose - to expose a replicated application as a service or route
extract - to extract secrets or config maps to disk
get - to display one or many resources
help - to get a list and description of all available CLI commands
idle - to idle scalable resources
image - to perform various operations on images
import-image - to import images from a container image registry
kustomize - to build a kustomization target from a directory or URL
label - to update the labels on a resource
login - to log into an OpenShift cluster
logout - to log out of OpenShift and end your current session
logs - to view logs for a particular container in a pod
new-app - to create a new application
new-build - to create a new build configuration
new-project - to create (or request to create) a new project
observe - to observe changes to resources and react to them (experimental)
options - shows a list of options that can be passed to any command
patch - to update fields of a resource
plugin - to list all visible plugin executables on a user's PATH
policy - to view or modify user policies
port-forward - to forward one or more local ports to a pod
process - to process a template into a list of resources
project - to view the current project or switch to another project.  
projects - to display existing projects
proxy - to run a proxy to the Kubernetes API server
registry - to log into or view information about the integrated registry
replace - to replace a resource by file name or by stdin
rollback - to revert part of an application back to a previous deployment
rollout - to start, stop, pause/show status of the rollout of a resource
rsh - to start a shell session in a container
rsync - to copy files between a local file system and a pod
run - to run a particular image on the cluster
scale - to set a new size for a deployment, replica set, or replication controller
secrets - to manage secrets
set - to set a wide range of parameters on a wide range of resources
start-build - to start a new build
status - to view info about the current working environment (project, services, deployments, and build configs)
tag - to tag existing images into image streams
version - to print the client and server version
wait - to wait for a specific condition on one or many resources (experimental)
whoami - see who you are logged in as.   whoami -c will asl show your context.
 
*events is in the documentation at  https://access.redhat.com/documentation/en-us/openshift_container_platform/4.13/html-single/cli_tools/index#openshift-cli-oc but not shown in tab completion of the oc command.
 

