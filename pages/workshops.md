<!DOCTYPE html>
<html>

  {% include head.html %}


    <body id="page-top" class="index">

    {% include header.html %}
    {% include workshop_table.html workshops=site.data.workshops.workshops_future %}
    <a href="{{ site.url}}/workshops">See all past and planned workshops</a>
    {% include footer.html %}
    {% include js.html %}

    </body>
</html>
