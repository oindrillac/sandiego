## Graphical Analysis for Discovering Important Open Source Projects

This directory mainly consists of 2 sections:
1. [Approaches](approaches) - This directory consists of detailed notebooks that explain the graphical approaches that we tried to discover emerging projects.
2. [Experiments](use-cases) - The notebooks in this directory use the methods tried out above for various use cases.

### Aim

* To identify new important emerging open source communities, usergroups, ecosystems and projects using graph representation techniques and algorithms.
* Use this knowledge and apply it to use-cases such as identifying new important projects for Red Hat, discover emerging projects that fit into a particular landscape and can be suitable to be hosted by a foundation.

### Approach

1. Use graphical network representation techniques to depict open source community data as nodes and edges.
2. Implement graph centrality algorithms, categorize important nodes in a network and leverage that information to identify important projects and user groups.
3. Validate the approaches by applying the above graphical techniques on the following use cases:
    * [openshift_and_kubernetes](approaches/openshift.ipynb) - Use historical GitHub data to track the emergence of important projects (eg: emergence of OpenShift as a downstream of Kubernetes).
    * [cncf_projects](approaches/cncf.ipynb) - Feed different groups of projects hosted by CNCF (graduated, incubating, sandbox) to the graph analysis methods and distinguish between these project groups graphically.
4. Use the validated approaches above to classify emerging projects of which are potentially interesting to Red Hat [emerging_projects_for_redhat](redhat.ipynb).