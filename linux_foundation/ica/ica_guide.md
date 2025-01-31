
# Istio Certification Study Guide

## My Thoughts on the Exam
**TBA**

### Why I Took the Exam
**TBA**

### About the Exam
**TBA**

### Book Your Exam Here
- [Istio Certified Associate (ICA)](https://training.linuxfoundation.org/certification/istio-certified-associate-ica/)

**The exam costs $250. Explore potential discounts through LF, CNCF or other initiatives.**
- [Linux-Foundation-Coupons - As of December 2024](https://github.com/CloudNativeStudyGroup/Linux-Foundation-Coupons) **Check this repo for possible active discount coupons**

**Includes:**  
1. Online proctored via PSI
2. Certification Valid for 2 Years  
3. Includes 12 Month Exam Eligibility  
4. Includes 1 Retake  
5. Performance-based & Multiple Choice Exam  
6. Duration of Exam 120 minutes  

---

## Domains, Competencies, and Information

### Istio Installation, Upgrade & Configuration (7%)
- **Using the Istio CLI to install a basic cluster**
  - [Istio Installation Guide](https://istio.io/latest/docs/setup/install/)
  - [istioctl Install Command](https://istio.io/latest/docs/setup/install/istioctl/)
- **Customizing the Istio installation with the IstioOperator API**
  - [IstioOperator Customization](https://istio.io/latest/docs/setup/install/istioctl/#customizing-the-configuration)
  - [IstioOperator API Reference](https://istio.io/latest/docs/reference/config/istio.operator.v1alpha1/)
- **Using overlays to manage Istio component settings**
  - [Using Overlays](https://istio.io/latest/docs/setup/install/istioctl/#customizing-installation-with-an-overlay)

### Traffic Management (40%)
- **Controlling network traffic flows within a service mesh**
  - [Traffic Management Overview](https://istio.io/latest/docs/concepts/traffic-management/)
  - [Virtual Service Configuration](https://istio.io/latest/docs/reference/config/networking/virtual-service/)
- **Configuring sidecar injection**
  - [Sidecar Injection](https://istio.io/latest/docs/setup/additional-setup/sidecar-injection/)
- **Using the Gateway resource to configure ingress and egress traffic**
  - [Ingress Gateway Configuration](https://istio.io/latest/docs/tasks/traffic-management/ingress/)
  - [Egress Gateway Configuration](https://istio.io/latest/docs/tasks/traffic-management/egress/)
- **Using ServiceEntry resources for adding entries to the internal service registry**
  - [ServiceEntry Configuration](https://istio.io/latest/docs/reference/config/networking/service-entry/)
- **Define traffic policies using DestinationRule**
  - [DestinationRule Configuration](https://istio.io/latest/docs/reference/config/networking/destination-rule/)
- **Configure traffic mirroring capabilities**
  - [Traffic Mirroring](https://istio.io/latest/docs/tasks/traffic-management/traffic-shifting/#mirroring)

## Resilience and Fault Injection (20%)
- Configuring circuit breakers (with or without outlier detection)
  - [Circuit Breakers](https://istio.io/latest/docs/tasks/traffic-management/circuit-breaking/)
- **Using resilience features**
  - [Retries and Timeouts](https://istio.io/latest/docs/tasks/traffic-management/retries-timeouts/)
- **Creating fault injection**
  - [Fault Injection](https://istio.io/latest/docs/tasks/traffic-management/fault-injection/)

## Securing Workloads (20%)
- Understand Istio security features
  - [Security Overview](https://istio.io/latest/docs/concepts/security/)
- **Set up Istio authorization for HTTP/TCP traffic in the mesh**
  - [Authorization Policies](https://istio.io/latest/docs/tasks/security/authorization/)
- **Configure mutual TLS at mesh, namespace, and workload levels**
  - [Mutual TLS Authentication](https://istio.io/latest/docs/tasks/security/authentication/)

## Advanced Scenarios (13%)
- **Understand how to onboard non-Kubernetes workloads to the mesh**
  - [Non-Kubernetes Workloads](https://istio.io/latest/docs/setup/additional-setup/mesh-expansion/)
- **Troubleshoot configuration issues**
  - [Istio Troubleshooting Guide](https://istio.io/latest/docs/ops/common-problems/network-issues/)

---

## Additional Resources

### Courses
- [Linux Foundation: Introduction to Istio (LFS144)](https://trainingportal.linuxfoundation.org/courses/introduction-to-istio-lfs144)
- [Youtube: Mesh Week (Session 1): Istio installation, upgrade & configuration](https://www.youtube.com/watch?v=w_8Gg_jsAbU)
- [Youtube: Mesh Week (Session 2): Istio Traffic management](https://www.youtube.com/watch?v=Q-l1z3ejc8Q)
- [Youtube: Mesh Week (Session 3): Istio Resiliency and fault injection](https://www.youtube.com/watch?v=df6A9PyhubQ)
- [Youtube: Mesh Week (Session 4): Security in Istio and securing workloads](https://www.youtube.com/watch?v=uO-X1U1l23I)
- [Youtube: Mesh Week (Session 5): Advanced scenarios and troubleshooting Istio](https://www.youtube.com/watch?v=Od7L-3tE9oA)
- [Youtube: Mesh Week: Mock Istio Certified Associate Exam](https://www.youtube.com/watch?v=AW8p3_pe64A)

### Practice Exams
- [Udemy: Labs - Exercise Istio Certified Associate - ICA](https://www.udemy.com/course/pe-lf-ica)
- [Udemy: Istio Certified Associate (ICA) Practice Exams](https://www.udemy.com/course/istio-certified-associate-practice-exams)

### Practice Labs
- [KillerCoda: Istio Certified Associate (ICA) - Lorenzo Gironi](https://killercoda.com/lorenzo-g) **These scenarios can be used standalone for ICA exam preparation or to learn and study Istio service mesh.**
- [KillerCoda: Istio Certified Associate (ICA) - Community | David Pech](https://killercoda.com/ica-scenarios) **Interactive Scenarios for the ICA from maintainers**

### Sources
- [Sajeeva Lakmal: How to Pass ICA (Istio Certified Associate) Exam](https://medium.com/@nvsajeeva/how-to-pass-ica-istio-certified-associate-exam-355152566bc8)
- [KodeKloud: Istio Service Mesh](https://learn.kodekloud.com/user/courses/istio-service-mesh) **Not a certification prep, but a good way to learn Istio and it comes with labs.**
- [Udemy: Istio Hands-On for Kubernetes](https://www.udemy.com/course/istio-hands-on-for-kubernetes)

### Time Spent 
**TBA**