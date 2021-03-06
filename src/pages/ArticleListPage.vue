<template>
  <TitleBar>게시물 리스트</TitleBar>

  <section class="article-write-form-box">
    <div class="container mx-auto">
      <form action="">
        <FormRow title="제목">
          <input
            type="text"
            class="form-row-input"
            placeholder="제목을 입력해 주세요."
          />
        </FormRow>
        <FormRow title="내용">
          <textarea
            class="form-row-input"
            placeholder="내용을 입력해 주세요."
          ></textarea>
        </FormRow>
        <FormRow title="작성">
          <div class="btns">
            <input type="button" value="작성" class="btn-primary" />
            <input type="button" value="작성" class="btn-secondary" />
            <input type="button" value="작성" class="btn-success" />
            <input type="button" value="작성" class="btn-danger" />
            <input type="button" value="작성" class="btn-warning" />
            <input type="button" value="작성" class="btn-info" />
          </div>
        </FormRow>
      </form>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import TitleBar from "../components/TitleBar.vue";

export default defineComponent({
  components: { TitleBar },
  name: "AppListPage",
});
</script>

<style scoped>
</style>
