In this post, a Windows 2019 server will be imported into Openshift Virtualization.  Step-by-step instructions will show the entire process to include:

Enabling Nested Virtualization

Creating the Windows VM inside of Qemu/KVM.

Installing the Openshift Virtualization Operator

Deploying the HostPath Provisioner since there is no other persistent storage (such as ODF or local storage operator) on this cluster.

Deploying the HyperConverged Custom Resource Definition.

Adding the QCOW boot source to the Windows 2019 Server template.

Creating the Windows VM from the template

These processes were tested in OCP 4.9 and 4.10.  This demonstration occurred on an OCP 4.9.35 SNO (single-node) cluster.

https://www.myopenshiftblog.com/example-of-deploying-a-windows-vm-from-a-template-using-openshift-virtualization/
