
# google.generativeai.get_model

<!-- Insert buttons and diff -->

<table class="tfo-notebook-buttons tfo-api nocontent">
<td>
  <a target="_blank" href="https://github.com/google/generative-ai-python/blob/master/google/generativeai/models.py#L33-L63">
    <img src="https://www.tensorflow.org/images/GitHub-Mark-32px.png" />
    View source on GitHub
  </a>
</td>
</table>



Calls the API to fetch a model by name.


<pre class="devsite-click-to-copy prettyprint lang-py tfo-signature-link">
<code>google.generativeai.get_model(
    name: model_types.AnyModelNameOptions,
    *,
    client=None,
    request_options: (helper_types.RequestOptionsType | None) = None
) -> (model_types.Model | model_types.TunedModel)
</code></pre>



<!-- Placeholder for "Used in" -->

```
import pprint
model = genai.get_model('models/gemini-1.5-flash')
pprint.pprint(model)
```

<!-- Tabular view -->
 <table class="responsive fixed orange">
<colgroup><col width="214px"><col></colgroup>
<tr><th colspan="2"><h2 class="add-link">Args</h2></th></tr>

<tr>
<td>

`name`<a id="name"></a>

</td>
<td>

The name of the model to fetch. Should start with `models/`

</td>
</tr><tr>
<td>

`client`<a id="client"></a>

</td>
<td>

The client to use.

</td>
</tr><tr>
<td>

`request_options`<a id="request_options"></a>

</td>
<td>

Options for the request.

</td>
</tr>
</table>



<!-- Tabular view -->
 <table class="responsive fixed orange">
<colgroup><col width="214px"><col></colgroup>
<tr><th colspan="2"><h2 class="add-link">Returns</h2></th></tr>
<tr class="alt">
<td colspan="2">

A <a href="../../google/generativeai/types/Model.md"><code>types.Model</code></a>

</td>
</tr>

</table>

