# file2

Open API spec file is sample2.yaml in the GitHub folder

{% swagger src="sample2.yaml" path="/suns" method="get" %}
[sample2.yaml](sample2.yaml)
{% endswagger %}

{% swagger src="sample2.yaml" path="/stars" method="post" %}
[sample2.yaml](sample2.yaml)
{% endswagger %}

{% swagger method="get" path="" baseUrl="blahj" summary="blah" %}
{% swagger-description %}
Hello
{% endswagger-description %}

{% swagger-parameter in="path" name="id" type="String" required="true" %}
id of the user
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Blah" %}

{% endswagger-response %}
{% endswagger %}
