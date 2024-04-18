<script>
  import ContainerWithHeader from '../elements/ContainerWithHeader.svelte';
  import ViewContainer from '../elements/ViewContainer.svelte';
  import Wallet from './Wallet.svelte';
</script>

<ContainerWithHeader>
  <div slot="body" class="w-full place-self-center">
    <div class="flex flex-col justify-center align-center items-center my-4 max-w-[360px] mx-auto gap-4">
      <h2 class="text-white text-xl">Please, connect your wallet</h2>
      <p class="text-white text-sm text-center">
        We couldn't detect a wallet.
        <br />
        Connect your wallet to continue.
      </p>
      <div class="max-w-[216px]">
        <Wallet />
      </div>
    </div>
  </div>
</ContainerWithHeader>
