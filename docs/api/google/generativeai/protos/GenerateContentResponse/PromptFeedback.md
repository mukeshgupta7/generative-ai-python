
# google.generativeai.protos.GenerateContentResponse.PromptFeedback

<!-- Insert buttons and diff -->

<table class="tfo-notebook-buttons tfo-api nocontent">
<td>
  <a target="_blank" href="https://github.com/googleapis/google-cloud-python/tree/main/packages/google-ai-generativelanguage/google/ai/generativelanguage_v1beta/types/generative_service.py#L507-L555">
    <img src="https://www.tensorflow.org/images/GitHub-Mark-32px.png" />
    View source on GitHub
  </a>
</td>
</table>



A set of the feedback metadata the prompt specified in ``GenerateContentRequest.content``.

<!-- Placeholder for "Used in" -->




<!-- Tabular view -->
 <table class="responsive fixed orange">
<colgroup><col width="214px"><col></colgroup>
<tr><th colspan="2"><h2 class="add-link">Attributes</h2></th></tr>

<tr>
<td>

`block_reason`<a id="block_reason"></a>

</td>
<td>

`google.ai.generativelanguage.GenerateContentResponse.PromptFeedback.BlockReason`

Optional. If set, the prompt was blocked and
no candidates are returned. Rephrase the prompt.

</td>
</tr><tr>
<td>

`safety_ratings`<a id="safety_ratings"></a>

</td>
<td>

`MutableSequence[google.ai.generativelanguage.SafetyRating]`

Ratings for safety of the prompt.
There is at most one rating per category.

</td>
</tr>
</table>



## Child Classes
[`class BlockReason`](../../../../google/generativeai/protos/GenerateContentResponse/PromptFeedback/BlockReason.md)

