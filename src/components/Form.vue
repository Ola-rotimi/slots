
import { slotFlagsText } from '@vue/shared';

<template>
  <form>
    <div class="help">
        <slot name="help" />
    </div>
    <div class="fields">
        <slot name="fields" />
    </div>
    <div class="buttons">
        <slot name="buttons" />
    </div>
    <slot />
  </form>
</template>
