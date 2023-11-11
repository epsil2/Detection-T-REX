
<div align=center>
  <img src="assets/eagle.png" width=900 >
</div>

<div align=center>
  <p >Eagle is an interactive object counting model that can first detect then count any objects through visual prompting</p>
</div>

<div align=center>

![Static Badge](https://img.shields.io/badge/Eagle-Alpha-blue) [![arXiv preprint](http://img.shields.io/badge/arXiv-2037.08723-b31b1b)](https://arxiv.org/pdf/2307.08723) [![Static Badge](https://img.shields.io/badge/Try_Demo!-blue?logo=chainguard&logoColor=green)](https://huggingface.co/spaces/Mountchicken/MAERec-Gradio) [![Homepage](https://img.shields.io/badge/homepage-visit-blue)](https://eagle-counting.github.io/) [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FMountchicken%2FEagle&count_bg=%2379C83D&title_bg=%23DF9B9B&icon=iconify.svg&icon_color=%23FFF9F9&title=VISITORS&edge_flat=false)](https://hits.seeyoufarm.com)

</div>


----

# What is Eagle 🦅
- Eagle is an object counting model that can first detect then count any objects through visual prompting, which is highlighted by the following features:
  - **Open-Set**: Eagle possess the capacity to count any object, without constraints on predefined categories.
  - **Visual Promptable**: Users can provide visual examples to specify the objects for counting.
  - **Intuitive Visual Feedback**: Eagle is a detection-based model that allows for visual feedback (i.e. detected boxes), enabling users to assess the accuracy of the result.
  - **Interactive**: Users can actively participate in the counting process to rectify any errors.

<!-- insert image in the middle -->
<div align=center>
  <img src="assets/about-img.png" width=400 >
</div>

# How Does Ealge Work ⚙️
- Eagle provides three major workflows for interactive object counting / detection.
  - **Positive-only Prompt Mode**: Eagle can detect then count similar objects in an image with just a single click or box drawing. Additional visual prompts can be added for densely packed or small objects.
  - **Positive with Negative Prompt Mode**: To address false detections caused by similar objects, users can correct the outcome by applying negative prompts to the erroneously detected objects.
  - **Cross Image Prompt Mode**: This feature supports counting across different reference and target images, ideal for automatic annotation. Users prompt on one image, and Eagle annotates the others automatically.

<div align=center>
  <img src="assets/workflow.png" width=700 >
</div>

# What Can Eagle Do 📝
- Eagle can be applyed to various domains for counting including but not limited to Agriculture, Industry, Livestock, Biology, Medical, Retail, Electronic, Transportation, Logistics, Human, etc. 
- Eagle can also serve as an open-set object detector, which can be applied for automatic annotaion. It process exponential zero-shot detection capability, and offers strong performance in dense and overlapping scenes.
- We list some of the potential applications of Eagle below:

<!-- There image each row -->
<div align=center>
  <img src="assets/1.png" width=300 >
  <img src="assets/2.png" width=300 >
  <img src="assets/3.png" width=300 >
</div>
<div align=center>

  <img src="assets/5.png" width=300 >
  <img src="assets/6.png" width=300 >
  <img src="assets/7.png" width=300 >
</div>


# Try Demo 🚀
- Waiting for DDS

# BibTeX 📚
```
Wating for technical report
```

# Acknowledgement 🙏
- We would like to thank the [DeepDataSpace](https://docs.deepdataspace.com/) team for building the demo.

# TODO List 📝
- [ ] A more detailed version of paper
- [ ] Release the code