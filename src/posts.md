---
layout: page
title: Blog
---

<ul class="list-disc list-inside space-y-4 text-xl">
  <% collections.posts.resources.each do |post| %>
    <li>
      <a href="<%= post.relative_url %>" class="text-blue-600 hover:underline">
        <%= post.data.title %>
      </a>
    </li>
  <% end %>
</ul>

