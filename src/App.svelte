<script>
import LoginEmailPage from './lib/LoginEmailPage.svelte';
import Router from "svelte-spa-router";

// import Loading from "./lib/Loading.svelte";


const routes = {
  "/": LoginEmailPage,
};
</script>

<Router {routes} />