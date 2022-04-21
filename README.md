# PCF-Sub-Business-Process-Flow
Business Process Flows (BPF) is one of the salient features that are available in Dynamics 365 but it doesn't have a provision to capture the sub-stages involved within a single stage, it can have various fields as steps but what if we can have a sub-business process flow that gives wide range of designs to give a better UX rather than an option set or checkbox.

This Sub-Business Process Flow control lets you capture the sub-stages with a fluid transition, let's you to have different styles for the stages, you can skip the stages, align the stages in a different direction like vertical & horizontal etc.  Well technically, it's a UI rich transition control, doesn't have any OOB BPF features but the workflow, plugins or any actions can be triggered on change of this since it overlays on an optionset field.  

## Configurable properties:
The number of stages - depends on the number of options in the optionset field on which the control is rendered.
Text of each stage - depends on the text of the options in the optionset field.
Style - different styles that are supported by Material UI.

## Steps:
Create an option set field, create options that need to be displayed as your stages in sub-BPF.
Open the field from the form, navigate to properties
Configure the design of the sub-BPF, currently, it supports 5 designs
Modifying the options in optionset will change the stages automatically

## Designs:
1. Linear Basic Bar
2. Linear Basic Dotted
3. Linear Basic Customized
4. Vertical
5. NonLinear (alert style stages)

![Syles available](https://i.imgur.com/fCnuStz.jpg)
Format: ![Alt Text](url)
