<script lang="ts">
  import svelteLogo from './assets/svelte.svg'
  import CurlyBraces from './lib/CurlyBraces.svelte'
  import Styles from './lib/Styles.svelte'
  import HtmlTags from './lib/HtmlTags.svelte'
  import Events from './lib/Events.svelte'
  import ReactiveDeclaration from './lib/ReactiveDeclaration.svelte'
  import ReactiveObjects from './lib/ReactiveObjects.svelte'
  import Props from './lib/Props.svelte'
  import IfElse from './lib/IfElse.svelte'
</script>

<main>
  <ul class="list">
    <li>
      <b>Curly braces:</b>
      <CurlyBraces />
    </li>
    <li>
      <b>Styles:</b>
      <Styles />
    </li>
    <li>
      <b>HTML tags:</b>
      <HtmlTags />
    </li>
    <li>
      <b>Events:</b>
      <Events />
    </li>
    <li>
      <b>Reactive declaration:</b>
      <ReactiveDeclaration />
    </li>
    <li>
      <b>Reactive object and array:</b>
      <ReactiveObjects />
    </li>
    <li>
      <b>Component props:</b>
      <Props />
      ...
      <Props def="Custom" />
      ...
      <Props {...{ def: 'Spread', text: 'text' }} />
    </li>
    <li>
      <b>If Else block:</b>
      <IfElse />
    </li>
  </ul>
</main>