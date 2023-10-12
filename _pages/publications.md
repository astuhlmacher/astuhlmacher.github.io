---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <a href="https://scholar.google.com/citations?user=usoAHLIAAAAJ&hl" target="_blank">my Google Scholar profile.</a>

## 2024

* A. Stuhlmacher, J. L. Mathieu, and P. Seiler, "Optimizing Dual-Axis Solar Panel Operation in an Agrivoltaic System and Implications for Power Systems", In: Proceedings of the 57th Hawaii International Conference on System Sciences (HICSS). Waikiki, Hawaii, January 2024.   
 
    <details>

    <summary> <em>Abstract</em></summary>
        The concept of agrivoltaics, or co-locating photovoltaic panels and crops, is viewed as a potential solution to competing land demands for food and energy production. In this paper, we propose an optimal dual-axis photovoltaic panel formulation that adjusts the panel position to maximize power generation subject to crop requirements. Through convex relaxations and shading factor approximations, we reformulate the problem as a convex second-order cone program and solve for the panel position adjustments away from the sun-tracking trajectory. We demonstrate our approach in a case study by comparing our approach with an approach that maximizes solar power capture and a scenario in which there are only crops. We found that we are able to successfully adjust the panel position while accounting for the trade-offs between the photovoltaic panels' energy production and the crop health. Additionally, optimizing the operation of an agrivoltaic system allows us to better understand agrivoltaic systems as a resource connected to the power grid.
    </details>


# 2023

* A. Stuhlmacher, S. Guikema, and J. L. Mathieu, "Assessing Network Resilience under an Optimal Water Pumping Control Strategy to Provide Frequency Regulation", In: (Review).


* C. Ten, A. Stuhlmacher, Y. Tang, and L. Dilworth, "Operational Planning for Emerging Distribution Systems: A Unique Perspective on Grid  Expansion", In: (Review).

* A. Stuhlmacher, "Optimal Scheduling and Control of Uncertain Coupled Power-Water Distribution Networks". PhD Thesis. University of Michigan. May 2023. DOI: [10.7302/7426](https://dx.doi.org/10.7302/7426).  

    <details>
    
    <summary> <em>Abstract</em></summary>
    Large amounts of renewable energy resources are being added to the electric power grid in a push to mitigate the effects of climate change. Due the intermittent and uncertain nature of these resources, more flexibility is needed to ensure safe operating conditions of the power grid. A growing body of research has shown that real-time control of flexible electric loads can provide flexibility to the power grid. For instance, drinking water distribution networks can be treated as flexible, controllable assets to the power grid by leveraging the power consumption of water supply pumps and storage capabilities of water tanks. Initial research has explored optimizing the operation of water distribution networks to support the power grid; however, the impact of uncertainty on network performance and value has not been considered. 
    
    In this dissertation, an integrated power-water optimization problem is developed subject to the water and power network constraints and multiple sources of uncertainty. The operation of water distribution networks is optimized to provide multiple local and system services-such as voltage and frequency regulation-to power networks. The integrated optimization of the water distribution network and power network is challenging because both networks have nonconvex models and experience uncertainty (e.g., water and power demands). Additionally, changes in network operation need to clearly provide value to both system operators as well as maintain or improve upon network resilience. The associated benefits and drawbacks of the integrated water-power optimization framework are investigated, with a particular focus on performance, conservativeness, and computational tractability. First, state and country-wide estimates of the power and energy capacity of water distribution networks as flexible loads are calculated using publicly available water distribution network utility information, indicating that water distribution networks can provide a sizable flexible resource. Second, stochastic and robust optimization frameworks are developed to optimally schedule and control the water distribution network to provide power system services while ensuring the safe operation of the power and water distribution networks given power and water demand uncertainties. Third, to address challenges surrounding problem complexity and scalability, this work develops proofs that the monotonicity properties apply to the water flow constraints under certain assumptions, uses approximation and relaxation techniques to reformulate the power-water problem as a convex program, and proposes an analytically reformulated probabilistic framework that manages uncertainty differently in the power and water network. Fourth, the flexibility of the water distribution network may be underutilized if any one power system service is considered. To prevent this, a formulation is developed where the water network provides multiple services simultaneously. This maximizes the overall benefit to the power grid and increases the value proposition to the water distribution network operator. And fifth, optimal pump operation strategies are evaluated to ensure that the power and water networks can respond and adapt to natural hazard events when the water distribution network is providing grid services. 
    
    Case studies demonstrate the capability of the water distribution network pumps to provide services to the power grid. By co-optimizing the power grid and the drinking water distribution network, improvement in costs, reliability, and resiliency can be realized across these two critical infrastructure systems. Additionally, leveraging the water distribution network to provide flexibility to the power grid can allow for greater quantities of renewable energy resources to be incorporated into the grid and reduce carbon emissions.
    </details>

# 2022

* A. Stuhlmacher and J. L. Mathieu, "Flexible Drinking Water Pumping to Provide Multiple Grid Services", In: Electric Power Systems Research - Special Issue for the 2022 Power Systems Computation Conference (PSCC), vol. 212, p. 108491. Porto, Portugal, June 2022. DOI: [10.1016/j.epsr.2022.108491](https://doi.org/10.1016/j.epsr.2022.108491).
    <details><summary> <em>Abstract</em></summary>
    Drinking water distribution networks (WDNs) can be operated as flexible, controllable loads. In this paper, we consider using WDNs to provide local and grid level services simultaneously to the power grid. We formulate a robust water pumping problem to determine the amount of voltage support and frequency regulation that can be provided subject to network constraints while managing power demand uncertainty. We tractably reformulate the problem as a sequential optimization problem and solve for the scheduled water pumping operation, the frequency regulation capacity, and the optimal control policy parameters that update the pump operation based on the frequency regulation signal and power distribution network demand forecast error. We demonstrate our approach through detailed case studies. Additionally, we evaluate the performance of the reformulation and discuss the benefits and trade-offs of WDNs providing multiple services.
    </details>

* A. Stuhlmacher and J. L. Mathieu, "Uncertainty-Aware Methods for Leveraging Water Pumping Flexibility for Power Networks", In: Proceedings of the IREP Symposium on Bulk Power System Dynamics and Control. Banff, Canada, August 2022. DOI: [10.48550/arXiv.2207.04943](https://doi.org/10.48550/arXiv.2207.04943).
    <details><summary> <em>Abstract</em></summary>
    Recent work has demonstrated that water supply pumps in the drinking water distribution network can be leveraged to provide flexibility to the power network, but existing approaches are computationally demanding and/or overly conservative.  In this paper, we develop a computationally tractable probabilistic approach to schedule and control water pumping to provide voltage support to the power distribution network subject to power and water distribution network constraints under power demand uncertainty. Building upon robust and chance-constrained reformulation approaches,  we analytically reformulate the probabilistic problem into a deterministic one and solve for the scheduled pump operation and the control policy parameters that adjust the pumps based on the power demand forecast error realizations. In a case study, we compare our proposed approach to an adjustable robust method and investigate the performance in terms of computation time, cost, and empirical violation probabilities. We find that our proposed approach is computationally tractable and is less conservative than the robust approach, indicating that our formulation would be scalable to larger networks. 
    </details>

# 2021

* A. Stuhlmacher, L. A. Roald, and J. L. Mathieu, "Tractable Robust Drinking Water Pumping to Provide Power Network Voltage Support", In: Proceedings of the Conference on Decision and Control (CDC). (virtual), pp. 4206-4213, December 2021. DOI: [10.1109/CDC45484.2021.9683419](https://doi.org/10.1109/CDC45484.2021.9683419).  

    <details>
    
    <summary> <em>Abstract</em></summary>
    Drinking water distribution networks can be treated as flexible, controllable assets for power distribution networks (e.g., to provide voltage support) by leveraging the power consumption of water pumps and storage capabilities of water tanks. We formulate an adjustable robust optimization problem to determine the scheduled water distribution network pumping and real-time pump adjustments that ensure that the power and water distribution network constraints are satisfied with respect to uncertain power demand. We extend the \m properties of dissipative flow networks to water distribution networks which requires assumptions on water tank operation. Then, to make the problem tractable, we leverage these properties, along with constraint approximations and an affine pump control policy, to reformulate the problem as an affinely adjustable robust counterpart that solves for the pumping schedule and the parameters of an affine control policy that determines the real-time pump adjustments. Through a case study, we demonstrate that the approach produces robust solutions and is computationally tractable. We also evaluate the impact of restricting water tank operation to enforce monotonicity and find it leads to a significantly restricted feasible region and more conservative solutions. 
    </details>

# 2020

* A. Stuhlmacher and J. L. Mathieu,"Chance-Constrained Water Pumping to Manage Water and Power Demand Uncertainty in Distribution Networks," In: Proceedings of the IEEE, vol. 108, no. 9, pp. 1640-1655. 2020. DOI: [10.1109/JPROC.2020.2997520](https://doi.org/10.1109/JPROC.2020.2997520).
    <details><summary> <em>Abstract</em></summary>
    Water pumping in drinking water distribution networks can be treated as a flexible load in the power distribution network. In this paper, we formulate an optimization problem to minimize the electricity costs associated with pumping subject to water and power distribution network constraints. In practice, both water and power demands are uncertain and pumps should be scheduled to ensure that pump operation does not violate either networks' constraints for nearly all possible uncertainty realizations. To address this problem, we formulate a chance-constrained optimization problem that simultaneously determines pumping schedules along with the parameters of real-time control policies that can be used to respond to water and power demand forecast errors. We use approximations and relaxations along with the scenario approach for chance-constrained programming to reformulate the optimization problem into a convex deterministic problem. We  demonstrate the performance of the approach through case studies, and also explore the impact of the relaxations, an approach to improve computational tractability, and trade-offs associated with the way in which we define the cost of real-time control actions. We find that optimal scheduling and real-time control of water pumping can effectively manage water and power demand uncertainty, meaning water demand is satisfied and both the water and power distribution networks operate within their limits; however, the approach is conservative leading to high reliability at high cost. 
    </details>

* A. Stuhlmacher and J. L. Mathieu,"Water Distribution Networks as Flexible Loads: A Chance-constrained Programming Approach", In: Electric Power Systems Research - Special Issue for the 2020 Power Systems Computation Conference (PSCC), vol. 188, p. 106570. (virtual), June 2020. DOI: [10.1016/j.epsr.2020.106570](https://doi.org/10.1016/j.epsr.2020.106570).
    <details><summary> <em>Abstract</em></summary>
    There is a greater need for flexibility in the power distribution network (PDN) due to increasing levels of renewable energy resources. Here, we consider using the water distribution network (WDN) as a flexible load. We formulate a chance-constrained multiperiod optimization problem to schedule water distribution pumps subject to WDN and PDN constraints while managing power demand forecast uncertainty. To do that, we develop a control policy that adjusts the WDN's operation when a PDN constraint violation is present. Since the resulting problem is nonconvex, we utilize approximation and relaxation techniques to transform the problem into a convex program and solve via the scenario approach. Through detailed case studies, we verify the performance of the control policy to ensure network constraints are satisfied despite uncertainty. We find that we can successfully schedule and control the WDN to provide flexibility to the PDN for many realistic water and power demand scenarios.
    </details>

# 2019

* A. Stuhlmacher and J. L. Mathieu, "Chance-Constrained Water Pumping Managing Power Distribution Network Constraints",  In: Proceedings of the North American Power Symposium (NAPS). Wichita, KS, October 2019. DOI: [10.1109/naps46351.2019.9000282](https://doi.org/10.1109/naps46351.2019.9000282).  

    <details>
    
    <summary> <em>Abstract</em></summary>
    We formulate a chance-constrained optimization problem to schedule water distribution network (WDN) pumping subject to water and power distribution network (PDN) constraints while managing water demand uncertainty. In addition to an optimal pumping schedule, we also determine optimal control policy parameters used to compute real-time control actions to compensate for demand forecast error. The resulting problem includes nonconvex constraints, and so conventional solution approaches for chance-constrained problems do not work. We heuristically apply a scenario-based method and investigate the control policy's performance to ensure all WDN and PDN constraints are satisfied despite uncertainty. Through case studies with a detailed model of a coupled WDN/PDN, we find that WDN pumping can be scheduled and controlled to manage PDN voltage constraints and that the scenario-based method provides feasible real-time control actions for many realistic water demand scenarios but more work is needed to identify computationally tractable approaches with probabilistic guarantees.
    </details>

