<template>
  <section class="flow section" data-padding="compact">
    <div class="wrapper" id="main">
      <div class="invoice-actions">
        <button class="show-invoices">📄 عرض الفواتير</button>
        <button class="upload-invoice">⬆️ رفع الفاتورة</button>
      </div>
    </div>
  </section>
</template>
<style scoped>
.invoice-actions {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 2rem;
}
button {
  width: 153px;
  height: 40px;
  border-radius: var(--border-radius-1);
}
.show-invoices {
  background-color: black;
  color: white;
  border: 1px solid #2c2c2c;
  border-radius: var(--border-radius-2);
}
.upload-invoice {
  border: 1px solid #d9d9d9;
}
</style>
