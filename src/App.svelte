<script lang="ts">
  import svelteLogo from './assets/svelte.svg'
  import CurlyBraces from './lib/CurlyBraces.svelte'
  import Styles from './lib/Styles.svelte'
  import HtmlTags from './lib/HtmlTags.svelte'
  import Events from './lib/Events.svelte'
  import ReactiveDeclaration from './lib/ReactiveDeclaration.svelte'
  import ReactiveObjects from './lib/ReactiveObjects.svelte'
  import Props from './lib/Props.svelte'
  import IfElse from './lib/IfElseBlock.svelte'
  import Each from './lib/EachBlock.svelte'
  import Await from './lib/AwaitBlock.svelte'
  import DomEvents from './lib/DomEvents.svelte'
  import ComponentEvents from './lib/ComponentEvents.svelte'
  import Binding from './lib/Binding.svelte'
  import BindingGroup from './lib/BindingGroup.svelte'
  import BindingSelect from './lib/BindingSelect.svelte'
  import BindingContenteditable from './lib/BindingContenteditable.svelte'
  import BindingDimensions from './lib/BindingDimensions.svelte'
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
    <li>
      <b>Each block:</b>
      <Each />
    </li>
    <li>
      <b>Await block:</b>
      <Await />
    </li>
    <li>
      <b>DOM events:</b>
      <DomEvents />
    </li>
    <li>
      <b>Component events:</b>
      <ComponentEvents on:message={(e) => alert(e.detail.text)} />
    </li>
    <li>
      <b>Binding:</b>
      <Binding />
    </li>
    <li>
      <b>Binding group:</b>
      <BindingGroup />
    </li>
    <li>
      <b>Binding select:</b>
      <BindingSelect />
    </li>
    <li>
      <b>Contenteditable binding:</b>
      <BindingContenteditable />
    </li>
    <li>
      <b>Dimensions:</b>
      <BindingDimensions />
    </li>
  </ul>
</main>