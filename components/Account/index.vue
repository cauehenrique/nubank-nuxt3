<template>
  <div class="bg-white text-black p-5 h-full relative">
    <h1 class="font-semibold text-lg">Conta</h1>
    <span class="text-2xl font-semibold">R$ 0,00</span>
    <div class="flex space-x-4 mt-6 overflow-x-auto">
      <AccountButton label="Área Pix">
        <IconCube />
      </AccountButton>
      <AccountButton label="Pagar">
        <IconDollar />
      </AccountButton>
      <AccountButton label="Transferir">
        <IconArrowUp />
      </AccountButton>
      <AccountButton label="Depositar">
        <IconArrowDown />
      </AccountButton>
      <AccountButton label="Recarga">
        <IconPhone />
      </AccountButton>
    </div>
    <button class="bg-gray-200 hover:bg-gray-300 p-3 rounded-lg font-semibold flex space-x-3 items-center w-full mt-5">
      <IconCard />
      <span>Meus cartões</span>
    </button>
    <Card />
  </div>
</template>
