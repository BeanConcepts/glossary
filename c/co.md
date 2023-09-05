# CO

| 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---|---|---|---|---|---|---|
| [A](../a/index.md) | [B](../m/index.md) | **C** | [D](../d/index.md) | [E](../e/index.md) | [F](../f/index.md) | [G](../g/index.md) | 
| [H](../h/index.md) | [I](../i/index.md) | [J](../j/index.md) | [K](../k/index.md) | [L](../l/index.md) | [M](../m/index.md) |[N](../n/index.md) | 
| [O](../o/index.md) | [P](../p/index.md) | [Q](../q/index.md) | [R](../r/index.md) | [S](../s/index.md) | [T](../t/index.md) | [U](../u/index.md) | 
| [V](../v/index.md) | [W](../w/index.md) | [X](../x/index.md) | [Y](../y/index.md) | [Z](../z/index.md) |
|   |   |   |   |   |   |   |
| [CA](ca.md) | [CB](cb.md) | [CC](cc.md) | [CD](cd.md) | [CE](ce.md) | [CF](cf.md) | [CG](cg.md) | 
| [CH](ch.md) | [CI](ci.md) | [CJ](cj.md) | [CK](ck.md) | [CL](cl.md) | [CM](cm.md) | [CN](cn.md) | 
| **CO** | [CP](cp.md) | [CQ](cq.md) | [CR](cr.md) | [CS](cs.md) | [CT](ct.md) | [CU](cu.md) | 
| [CV](cv.md) | [CW](cw.md) | [CX](cx.md) | [CY](cy.md) | [CZ](cz.md) |

## Cohesion
### Module Cohesion
- manner and degree to which the **tasks performed** by a single software module are **related to one another** [1, Sec. 3.625]
- in software design, a **measure of the strength of association** of the **elements within a module** [1, Sec. 3.625] [2, Sec. 2.1.4]
cf. coupling
#### Contains
- 7 types: coincidental, temporal, logical, sequential, procedural, communicational, and functional.

## Common-environment Coupling
### Common-envrionment Module Coupling
- type of coupling in which two software modules access a common data area [1, Sec. 3.654]
#### Type of
- [Module Coupling](co.md#module-coupling)

## Content Coupling
### Content Module Coupling
- type of coupling in which **some or all** of the **contents** of one software module are **included** in the contents of
another module [1, Sec. 3.816]
#### Type of
- [Module Coupling](co.md#module-coupling)

## Control Coupling
### Control Module Coupling
- type of coupling in which one software module **communicates** information to another module for the explicit
**purpose of influencing** the latter module's **execution** [1, Sec. 3.853]
#### Type of
- [Module Coupling](co.md#module-coupling)

## Control plane
- The container orchestration layer that exposes the API and interfaces to define, deploy, and manage the lifecycle of containers.

### Contains
- 5 components: etcd, API Server, Scheduler, [Controller Manager](co.md#Kubernetes-Controller-Manager), Cloud Controller Manager


## Controllers
### Kubernetes Controllers
- controllers are control loops that watch the state of your cluster, then make or request changes where needed. Each controller tries to move the current cluster state closer to the desired state.

### Kubernetes Controller Manager
- Control plane component that runs controller processes, but to reduce complexity, they are all compiled into a single binary and run in a single process.

## Coupling
### Module Coupling
- manner and degree of **interdependence between software modules** [1, Sec. 3.919]
- **strength of the relationships** between modules [1, Sec. 3.919)
- **measure of how closely connected** two routines or modules are [1, Sec. 3.919]
- in software design, a **measure of the interdependence** among modules in a computer program [1, Sec. 3.919] [2, Sec. 2.1.4]
#### Contains
- 6 types: pathological, [control](co.md#control-coupling), hybrid, data, [content](co.md#content-coupling), common-environment

## References
[1] "ISO/IEC/IEEE International Standard - Systems and software engineering--Vocabulary," in ISO/IEC/IEEE 24765:2017(E) , vol., no., pp.1-541, 28 Aug. 2017, doi: 10.1109/IEEESTD.2017.8016712.

[2] P. Bourque and R. E. Fairley, Guide to the Software Engineering Body of Knowledge. Los Alamitos, CA: IEEE Computer Society, 2014.
