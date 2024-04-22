<script>
  import ContainerWithHeader from '../elements/ContainerWithHeader.svelte';
  import Wallet from './Wallet.svelte';
</script>

<div
  class="flex flex-col justify-center align-center items-center content-center text-center max-w-[600px] mx-auto my-10 lg:mt-40"
>
  <ContainerWithHeader>
    <div slot="body" class="w-full place-self-center p-4 lg:p-10">
      <div class="flex flex-col gap-6">
        <h2 class="text-white text-xl">Please, connect your wallet</h2>
        <p class="text-white text-sm text-center">
          We couldn't detect a wallet.
          <br />
          Connect your wallet to continue.
        </p>
        <div class="max-w-[216px] mx-auto">
          <Wallet />
        </div>
      </div>
    </div>
  </ContainerWithHeader>
</div>
