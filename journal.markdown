---
layout: default
title: Journal
permalink: /journal/
---
<div class="bg-gray-100 text-off-black py-20 md:py-32">
  <div class="container mx-auto px-6">
    <div class="text-center max-w-3xl mx-auto pt-16">
      <h1 class="text-4xl md:text-6xl font-eraz font-bold tracking-tight">Journal</h1>
      <p class="mt-4 text-lg text-gray-600">Developments, thoughts, and breakthroughs from the lab.</p>
    </div>

    <!-- Blog Feed -->
    <div class="mt-16 max-w-3xl mx-auto space-y-20">
      {% for post in site.posts %} 
        <div class="{% cycle 'bg-gray-100', 'bg-gray-50' %} rounded-2xl p-8 md:p-12">
          <article class="prose lg:prose-lg prose-headings:font-eraz prose-headings:tracking-tight prose-a:text-neon-green hover:prose-a:text-green-700 max-w-none">
            <header class="text-center border-b border-gray-200 pb-8">
              <p class="text-sm text-gray-500 mb-2">{{ post.date | date: "%B %d, %Y" }}</p>
              <a href="{{ post.url | relative_url }}" class="no-underline hover:no-underline"><h2 class="!text-4xl !mb-0">{{ post.title }}</h2></a>
            </header>
            <div class="mt-8">
              {{ post.content }}
            </div>
          </article>
        </div>
      {% endfor %}
    </div>
  </div>
</div>