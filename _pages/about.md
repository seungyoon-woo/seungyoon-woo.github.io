---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<p style="font-size:15px;">Hi! I'm Seungyoon Woo, a Ph.D. student in the Graduate School of AI at Seoul National University, advised by Prof. Gunhee Kim in the Vision &amp; Learning Lab. I work on AI safety, continual learning, and memory-based agents. [<a href="{{ base_path }}/files/Seungyoon_Woo_CV.pdf">CV</a>]</p>

<p style="font-size:15px;">Models keep changing after they ship. Users fine-tune them, agents write to their own memory, and the environment shifts under them. Each of these updates can erode safety behavior the way a continual learner forgets old tasks. I want to build AI that keeps learning as long as it runs and stays aligned through those updates. It should tell you which of its changes came from the world and which came from its own mistakes.</p>

<p style="font-size:15px; margin-bottom:4px;">My work follows three threads:</p>
<ul style="font-size:15px;">
  <li><b>Alignment as retention.</b> Safety training can suppress harmful behavior without removing it, and later fine-tuning can bring that behavior back. I treat this as a forgetting problem and use continual-learning tools to make safety last.</li>
  <li><b>Continual learning.</b> I build modular methods that let a model take on new tasks without overwriting old ones. COMET (NeurIPS 2026) applies this to vision-language models with no task labels at inference, and MCL-NF (ICLR 2025) extends meta-continual learning to neural fields.</li>
  <li><b>Memory-based agents.</b> A deployed agent serves many users across many sessions, and what they tell it shifts and sometimes conflicts. I want to build memory systems that work without failure in these dynamic, interactive settings. The agent should keep each user's context apart, update its beliefs when the world changes, and stop one session from corrupting another.</li>
</ul>

Recent News!
======
<p style="font-size:15px; margin-bottom:4px;">Our paper "COMET: Decoupled Distillation, Routing, and Capacity Control for Task-Agnostic Continual Vision–Language Learning" was accepted to NeurIPS 2026!</p>
<p style="font-size:15px;">Our paper "Meta-Continual Learning of Neural Fields" was accepted in ICLR 2025!</p>

Publications
======
<p style="font-size:15px; margin-bottom:2px; margin-top:0px"><b>COMET: Decoupled Distillation, Routing, and Capacity Control for Task-Agnostic Continual Vision–Language Learning</b></p>
<div class="pub_item" style="display:inline-flex; flex-wrap:wrap; padding-bottom:20px;">
  <div class="pub_img" style="width:270px; object-fit:cover;">
    <a href="{{ base_path }}/images/comet.png"><img src="{{ base_path }}/images/comet.png" alt="COMET Overview"></a>
  </div>
  <div class="pub_detail" style="margin-left:10px; max-width:340px">
    <p style="font-size:13px; margin-bottom:2px"><b>Seungyoon Woo</b>, Keonhee Park, Gunhee Kim. NeurIPS 2026 [<a href="{{ base_path }}/files/comet_neurips2026.pdf">PDF</a>]</p>
    <p style="font-size:13px; margin-bottom:2px">COMET treats distillation, routing, and capacity control as separate components of a modular continual learner for vision-language models. Keeping them apart reduces catastrophic forgetting, and the model needs no task labels at inference.</p>
  </div>
</div>

<p style="font-size:15px; margin-bottom:2px; margin-top:0px"><b>Meta-Continual Learning of Neural Fields</b></p>
<div class="pub_item" style="display:inline-flex; flex-wrap:wrap; padding-bottom:20px;">
  <div class="pub_img" style="width:270px; object-fit:cover;">
    <img src="{{ base_path }}/images/FIM.png" alt="MCLNF Overview">
  </div>
  <div class="pub_detail" style="margin-left:10px; max-width:340px">
    <p style="font-size:13px; margin-bottom:2px"><b>Seungyoon Woo</b>, Junhyeog Yun, Gunhee Kim. ICLR 2025 [<a href="{{ base_path }}/files/mclnf_iclr2025.pdf">PDF</a>]</p>
    <p style="font-size:13px; margin-bottom:2px">This work addresses Meta-Continual Learning of Neural Fields (MCL-NF), a novel framework that combines modular architecture with optimization-based meta-learning to enhance the continual learning of neural fields. The framework employs Fisher Information Maximization Loss to optimize learning generalization and resource efficiency, particularly in resource-constrained environments.</p>
  </div>
</div>

Education
======
<p style="font-size:15px; margin-bottom:2px"><b>M.S/Ph.D in Graduate School of AI (2022.9 - )</b></p>
<p style="font-size:15px; margin-bottom:2px">Seoul National University</p>
<p style="font-size:15px; margin-bottom:12px">Advisor: Gunhee Kim</p>
