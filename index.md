---
layout: index
sectionid: home
---

<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css" rel="stylesheet">

<div class="header-container jumbotron">
    <div class="container">
        <h1>Comprehensive Assessment of Jailbreak Attacks Against LLMs</h1>
        <p>TL;DR: This study presents the first large-scale, comprehensive and unified measurement of various jailbreak attacks against LLMs, revealing the need for improved alignment of LLM policies and countermeasures, emphasizing the necessity of evaluating different jailbreak methods.</p>
        <p><a class="btn btn-primary btn-lg" href="https://arxiv.org/abs/2402.05668" role="button">Learn more</a></p>
    </div>
</div>

<div class="container">
    <div class="row">
        <div class="col-md-6">
            <h2 class="header-light regular-pad" style="font-size: 40px;">Abstract</h2>
              <p class="lead">
              <i>Jailbreak attacks</i> aim to bypass the safeguards of LLMs.
              While researchers have studied different jailbreak attacks in depth, they have done so in isolation - either with unaligned experiment settings or comparing a limited range of methods.
              To fill this gap, we present the first large-scale measurement of various jailbreak attack methods. 
              We collect 14 cutting-edge jailbreak methods and establish a jailbreak attack taxonomy.
              We then conduct a unified and impartial assessment of attack effectiveness based on six popular censored LLMs and 160 questions from 16 violation categories.
              </p>
        </div>
        <div class="col-md-6 text-center">
            <img src="{{ "/assets/img/overview.png" | relative_url }}" alt="Overview" class="img-responsive" width="80%" style="margin-top: 40px; margin-left: 40px;">
        </div>
    </div>
    <hr>
    <div class="row">
        <div class="col-sm-4">
            <h1 class="text-center"><i class="fa-solid fa-sitemap" aria-hidden="true"></i></h1>
            <h3 class="text-center">Jailbreak Taxonomy</h3>
            <p>
              We classify the methods based on two criteria: 
              (1) whether the original forbidden question is modified;
              (2) how these modified prompts are generated in the method.
            </p>
        </div>
        <div class="col-sm-4">
            <h1 class="text-center"><i class="fa-solid fa-file-shield" aria-hidden="true"></i></h1>
            <h3 class="text-center">Unified Usage Policy</h3>
            <p>
              We collect and summarize the usage policies from five major LLM-related service providers (Google, OpenAI, Meta, Amazon, and Microsoft).
            </p>
        </div>
        <div class="col-sm-4">
            <h1 class="text-center"><i class="fa-solid fa-gears" aria-hidden="true"></i></h1>
            <h3 class="text-center">Unified Settings</h3>
            <p>
              We align the experimental settings, especially the number of steps in the optimization process, to provide an unbiased and fair experimental setup as much as possible.
            </p>
        </div>
    </div>
</div>
