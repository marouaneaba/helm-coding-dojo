### Charts:
Charts are the package format used by Helm. They define a set of resources to be deployed to a Kubernetes cluster. Functionally, charts are comparable to an apt, yum or homebrew.


### Repositories:

Repositories are locations where charts can be collected and distributed. They’re similar in function to apt or rpm repositories.


### Helm util:

A Releases represent an instance of a chart running in a Kubernetes cluster. If a chart is installed multiple times into the same Kubernetes cluster, it will be given a unique release with a corresponding name each time.
4.In other words, Helm is used to install charts into Kubernetes clusters. The installation of a chart creates a release. To locate Helm charts for deployment, one would search a Helm chart repository.
