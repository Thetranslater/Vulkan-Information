# Vulkan-Information
a information header about vulkan structures

Because vulkan has **a lot** structures and most sturctures have several fixed value(such as `sType` or `flags`) and complex meaning fields, developer (at least me) often should check the sepcification for help when populate the sturctures.

So here is a extremely simple header to give some comments about the vulkan sturctures. With the function of display comments when your cursor move to the function when using a code editor or IDE or some plugins, you can quckily view the fields of one sturcture. Also, i give a brief explanation about every fileds so you don't have to switch between editor and specification (if you know the structures meanings).

You just include the header in you code and use it like this
```
VkGraphicsPipelineCreateInfo createInfo = VulkanInfo::aboutVkGraphicsPipelineCreateInfo();
```

The basic of the header only describe most structures in vulkan 1.0 for now
