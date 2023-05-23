# Healty App
## summary
This is the git repository of the design of BDI agent in gwendolen language of health app for privacy in data collection stage for the submission of JELIA 2023.

## file descriptions
- file .gwen: this is the file for the design of a multi-agent systems using gwendolen languages;
- file .psl: this is the file for the specification of the formal properties of the resulting agent system;
- file .ail: this is the file to execute the simulation of the resulting agent system;
- file .jpd: this is the file to verification the implementation of the resulting agent system.

## instructions on reproducibility
- step 1: please go to github page to install MCAPL framework: https://github.com/mcapl/mcapl
- step 2: to execute the simulation of this agent system, run the command: java ail.mas.AIL ${path_to}/health_app.ail
- step 3: to verify the implementation of this agent system, run the command: java gov.nasa.jpf.tool.RunJPF ${path_to}/health_app.jpf
- step 4: to change the property under verification: change the number **n** in target.args =${path_to}/fitness_app.psl,**n** in health_app.jpf file

## Note
If you need any help, in particular, setting up MCAPL framework, please do not hesitate to contact Mengwei at mengwei.xu@manchester.ac.uk
