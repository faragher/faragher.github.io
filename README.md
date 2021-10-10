## Development Notes
I am not a programmer or a developer. This is all new to me. So I heve to come at problems from a different perspective, and maybe that means that someone else can learn something from an outside perspective.

Or maybe I'm just noting down this stuff down so I remember it. Doesn't matter.

### Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
