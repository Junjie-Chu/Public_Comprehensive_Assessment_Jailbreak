---
layout: default
---

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
            <h2 class="header-light regular-pad">Abstract</h2>
              <p class="lead">Misuse of the Large Language Models (LLMs) has raised widespread concern. To address this issue, safeguards have been taken to ensure that LLMs align with social ethics. However, recent findings have revealed an unsettling vulnerability bypassing the safeguards of LLMs, known as jailbreak attacks. By applying techniques, such as employing role-playing scenarios, adversarial examples, or subtle subversion of safety objectives as a prompt, LLMs can produce an inappropriate or even harmful response. While researchers have studied several categories of jailbreak attacks, they have done so in isolation. To fill this gap, we present the first large-scale measurement of various jailbreak attack methods. We concentrate on 13 cutting-edge jailbreak methods from four categories, 160 questions from 16 violation categories, and six popular LLMs. Our extensive experimental results demonstrate that the optimized jailbreak prompts consistently achieve the highest attack success rates, as well as exhibit robustness across different LLMs. Some jailbreak prompt datasets, available from the Internet, can also achieve high attack success rates on many LLMs, such as ChatGLM3, GPT-3.5, and PaLM2. Despite the claims from many organizations regarding the coverage of violation categories in their policies, the attack success rates from these categories remain high, indicating the challenges of effectively aligning LLM policies and the ability to counter jailbreak attacks. We also discuss the trade-off between the attack performance and efficiency, as well as show that the transferability of the jailbreak prompts is still viable, becoming an option for black-box models. Overall, our research highlights the necessity of evaluating different jailbreak methods. We hope our study can provide insights for future research on jailbreak attacks and serve as a benchmark tool for evaluating them for practitioners.</p>
        </div>
        <div class="col-md-6 text-center">
            <img src="{{ "/assets/img/overview.png" | relative_url }}" alt="Overview" class="img-responsive">
        </div>
    </div>
    <hr>
    <div class="row">
        <div class="col-sm-4">
            <h1 class="text-center"><i class="fa fa-pencil" aria-hidden="true"></i></h1>
            <h3 class="text-center">Jailbreak Taxonomy</h3>
            <p>Get started by cloning source into GitHub account of your project. Thanks to <a href="https://pages.github.com">GitHub Pages</a>,
              it will be automatically compiled and published under your account's (or organisation's) subdomain under <code>github.io</code>.
            </p>
        </div>
        <div class="col-sm-4">
            <h1 class="text-center"><i class="fa fa-cogs" aria-hidden="true"></i></h1>
            <h3 class="text-center">Unified Usage Policy</h3>
            <p>This template uses <a href="https://github.com/twbs/bootstrap-sass">bootstrap-sass</a> along with <a href="https://bootswatch.com/">Bootwatch themes</a>.
            You can change the theme or write your custom one by overwriting bootstrap sass variables for a different color set, font options, etc.</p>
        </div>
        <div class="col-sm-4">
            <h1 class="text-center"><i class="fa fa-code-fork" aria-hidden="true"></i></h1>
            <h3 class="text-center">Unified Settings</h3>
            <p>Leverage from Git version control system by
              maintaining your documentation along with the source code; publish the page when you merge to the master branch.</p>
        </div>
    </div>
</div>
