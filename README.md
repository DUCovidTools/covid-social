# Social Interventions COVID-19 agent-based model

This repository contains the model code and documentation for the Social Interventions COVID-19 agent-based model, which is built in the specialist simulation software **NetLogo**. You will need to install NetLogo, version 6.1 or later, which is available as a free download from https://ccl.northwestern.edu/netlogo/. Open the model file (Social COVID-19s.nlogo) in NetLogo to access the main user interface.

In the absence of a vaccine or effective treatment, the only way to manage a communicable disease epidemic is to interrupt transmission from infectious people to susceptible people. This involves controlling the ways in which people mix (such as isolating those potentially exposed) and reducing the potential for transmission where they do mix (such as promoting good hand hygiene). This model is intended to help understand the potential impact of combinations of these non-pharmaceutical interventions over time, and the uncertainties associated with estimates of the impact.

Two processes are represented in the model: transmission and disease progression. These interact through an extended person to person SEIR epidemic model. The disease spreads directly from infectious people to susceptible people, excluding indirect real-world paths such as virus survival on hard surfaces. The interventions act on the transmission process, for example constraining the mixing between infectious and susceptible people. Once the disease has been successfully transmitted to a susceptible person, that person progresses through different epidemic states, which may include hospitalisation.
