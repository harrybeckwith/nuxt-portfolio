<template>
    <div>
        <h1 class="title italic">
            Vuex — how to use state
        </h1>
        <p>
            When an app becomes complex in terms of where data is being passed between multiple components, it is time to make use of Vuex.
        </p>
        <p>
            Vuex is a state management pattern + library for Vue.js applications. It serves as a centralized store for all the components in an application, with rules ensuring that the state can only be mutated in a predictable fashion.
        </p>
        <img src="~assets/images/vuex/vuex.png" alt="vuex chart" class="image">
        <h3 class="italic title--page">
                Why use Vuex?
        </h3>
        <ul class="list list--bullet">
            <li>
                Vuex provides one source of truth
            </li>
            <li>
                Every component has access to the global state
            </li>
             <li>
                The global state is reactive, just like local state
            </li>
            <li>
                Reduces component data tracking from becoming complex.
            </li>
            <li>
                Vuex provides a state pattern to make updates standardized.
            </li>
        </ul>
        <p>
            To set up Vuex you have to install the npm package.
        </p>
<pre><code class="language-css">p { color: red }</code></pre>

    </div>
</template>
<script>
export default {
    layout: 'blog',
};
</script>