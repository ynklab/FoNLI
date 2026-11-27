# FoNLI
This is an natural language inference (NLI) dataset for Japanese focus particles.

## About the dataset
This dataset is constructed based on [Japanese semantic test suite (JSeM)](https://github.com/DaisukeBekki/JSeM).

### Data Example
```xml
<problem answer="no" inference_type="presupposition?" jsem_id="Tor1-1" language="jp" phenomena="Toritate, -sika (toritate particle), Negation">
    <description>《「しか」のbasic example》</description>
    <p idx="1">
      <script>太郎しかレポートを出さなかった。</script>
    </p>
    <h>
      <script>太郎はレポートを出さなかった。</script>
    </h>
    <note>
    取り立て詞の除去：しか。前提かもしれないのでinference_typeをpresupposition?にした。</note>
</problem>
```
* `id`: `Tor1` is the ID of the original instance in JSeM
* `phenomena`: contains what focus particle the instance addresses

## Contact
If you have any questions or feedback, please open an issue. For private inquiries, please contact ymikami(at)is.s.u-tokyo.ac.jp