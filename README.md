# SCEA v1.0 - Smart Contract English Auction Simulation

## Overview

This project is an AnyLogic simulation model named **SCEA v1.0** which stands for Smart Contract English Auction version 1.0. It is designed to simulate and analyze the dynamics of English Auctions within a smart contract framework. The model is built using AnyLogic simulation software and explores various aspects of auction mechanisms, particularly focusing on:

*   **Shill Bidding:** Investigating the impact of shill bidders on auction outcomes.
*   **Shield Mechanisms:**  Analyzing the effectiveness of shield mechanisms in mitigating shill bidding and enhancing auction fairness.

This simulation model is developed for research purposes and allows for experimentation with different auction parameters and bidder strategies.

**Main Project File:**

*   `SCEA v1.0.alp`: This is the primary AnyLogic project file. You will need AnyLogic software (version 8.9.3 or later recommended) to open and run this model.

**Project Folders:**

*   `shield`: This folder likely contains experiments and scenarios specifically designed to test and analyze shield mechanisms within the auction.
*   `Shill Experiment`: This folder probably includes experiments focused on simulating and observing the effects of shill bidding strategies on the auction dynamics.

## Contributors

*   **Sajed Yousefi Mashhour** - Contributor to the AnyLogic model development.

## Supervisors

*   **Dr. Alireza Hashemi Golpayegani** - Research Supervisor.
*   **Dr. Sara Salimi Namin** - Research Supervisor.

## How to Run the Model

To run the SCEA v1.0 simulation model, you will need to have **AnyLogic simulation software** installed on your machine.

1.  **Download and Install AnyLogic:** If you do not have AnyLogic, you can download a free learning edition or a professional version from the [AnyLogic website](https://www.anylogic.com/).
2.  **Open the Project:** Launch AnyLogic and open the `SCEA v1.0.alp` file.
3.  **Explore and Run Experiments:**
    *   Navigate through the project structure in the AnyLogic Project window.
    *   Explore the 'Main' experiment and other defined experiments (like those in "shield" or "Shill Experiment" if they are set up as separate experiments in AnyLogic).
    *   Adjust parameters in the 'Main' experiment or specific experiment configurations as needed.
    *   Run the simulation by clicking the 'Run' button and selecting the desired experiment to execute.
4.  **Analyze Results:** Observe the simulation outputs, logs, and any visual dashboards created within the AnyLogic model to analyze the results of your experiments.

## Model Parameters (Partial List)

The model is parameterized to allow for flexible experimentation. Some key parameters you can adjust within the 'Main' agent of the AnyLogic model include:

*   **`p_TotalBidders`**:  (Integer) -  Specifies the total number of bidders participating in the auction.
*   **`p_ShillPercentage`**: (Double) -  Determines the percentage of bidders who are shill bidders.
*   **`p_ShieldBidder`**: (Boolean) -  Indicates whether a shield bidder is present in the auction.
*   **`p_IsShieldAcitve`**: (Boolean) -  Activates or deactivates the shield mechanism in the simulation.
*   **`p_AuctionDuration`**: (Integer, Time Unit: HOUR) - Sets the duration of the auction.
*   **`p_HasPrevention`**: (Boolean) -  Potentially related to implementing preventative measures against shill bidding (needs further investigation within the model).
*   **`p_ForceStopShills`**: (Boolean) -  May control the behavior of shill bidders, possibly forcing them to stop bidding under certain conditions.

**Note:** This is a partial list of parameters extracted from the provided `SCEA v1.0.alp` file. A full understanding of all parameters and model functionalities requires opening the `SCEA v1.0.alp` project in AnyLogic and examining the model logic.
