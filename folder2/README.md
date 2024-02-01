# file2
Testing PR flow
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

<table><thead><tr><th>Col1</th><th>SelectColumn<select><option value="5eee7c8cae474f3fbe002e4cec869129" label="Opt 1" color="blue"></option><option value="82722c0e76884005a62678aba9d91cd4" label="Opt 2" color="blue"></option><option value="3b26fa45cd2d42568a3904564494015f" label="Opt 3" color="blue"></option></select></th></tr></thead><tbody><tr><td>col12</td><td><span data-option="5eee7c8cae474f3fbe002e4cec869129">Opt 1</span></td></tr><tr><td>col23</td><td><span data-option="82722c0e76884005a62678aba9d91cd4">Opt 2</span></td></tr><tr><td>col34</td><td><span data-option="3b26fa45cd2d42568a3904564494015f">Opt 3</span></td></tr></tbody></table>

Testing GitSync
