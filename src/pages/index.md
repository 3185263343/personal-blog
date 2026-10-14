---
layout: ../../src/layouts/BaseLayout.astro
title: 欢迎来到我的博客
description: 个人博客首页
---

<section class="content-shell py-20 md:py-28">
  <div class="grid items-center gap-10 md:grid-cols-[1.2fr_0.8fr]">
    <div>
      <p class="text-sm uppercase tracking-[0.32em] text-slate-500">Portfolio • Journal</p>
      <h1 class="mt-5 text-4xl md:text-6xl font-semibold leading-tight tracking-tight text-slate-900">
        端庄大气，记录生活与思考。
      </h1>
      <p class="mt-6 max-w-xl text-lg leading-8 text-slate-600">
        这是一个以温和、稳重、现代感为主的个人博客示例页面，适合记录文章、观点、作品和生活。
      </p>
      <div class="mt-8 flex flex-wrap gap-4">
        <a href="/posts/" class="rounded-xl bg-slate-900 px-5 py-3 text-sm font-medium text-white shadow-lg shadow-slate-300/40 transition hover:-translate-y-0.5">阅读文章</a>
        <a href="#about" class="rounded-xl border border-slate-200 bg-white px-5 py-3 text-sm font-medium text-slate-700 transition hover:-translate-y-0.5">关于我</a>
      </div>
    </div>

    <div class="rounded-[2rem] border border-slate-200 bg-white p-6 shadow-[0_20px_60px_rgba(15,23,42,0.08)]">
      <div class="rounded-[1.5rem] bg-gradient-to-br from-slate-900 via-slate-700 to-slate-500 p-6 text-white">
        <p class="text-sm uppercase tracking-[0.2em] text-slate-200">Profile</p>
        <h2 class="mt-4 text-3xl font-semibold">个人简介</h2>
        <p class="mt-4 text-sm leading-7 text-slate-100">
          热爱设计、写作与创造性工作，致力于用简洁有力的表达方式，让内容更清晰、更值得被记住。
        </p>
      </div>
      <div class="mt-6 grid grid-cols-3 gap-3 text-center">
        <div class="rounded-2xl bg-slate-50 p-4">
          <div class="text-2xl font-semibold text-slate-900">5+</div>
          <div class="text-xs text-slate-500">年经验</div>
        </div>
        <div class="rounded-2xl bg-slate-50 p-4">
          <div class="text-2xl font-semibold text-slate-900">24</div>
          <div class="text-xs text-slate-500">文章</div>
        </div>
        <div class="rounded-2xl bg-slate-50 p-4">
          <div class="text-2xl font-semibold text-slate-900">8</div>
          <div class="text-xs text-slate-500">项目</div>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="about" class="content-shell py-8 md:py-16">
  <div class="rounded-[2rem] border border-slate-200 bg-white p-8 shadow-sm">
    <p class="text-sm uppercase tracking-[0.3em] text-slate-500">About</p>
    <h2 class="mt-4 text-3xl font-semibold text-slate-900">关于这个站点</h2>
    <p class="mt-4 max-w-3xl text-slate-600 leading-8">
      这个博客源于对“克制、质感与信息秩序”的理解：它不追求炫目繁复，而在细节与留白之间寻找平衡，让内容最先被看到、最容易被理解，并能够长久留在读者心里。
    </p>
  </div>
</section>
