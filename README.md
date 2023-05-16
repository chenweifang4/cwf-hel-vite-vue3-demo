# cwf-hel-vite-vue-demo

## 快速上手

### 安装依赖

```bash
pnpm install
```

### cwf-hel-vite-vue3-demo-remote

> 远程模块，供 host 消费

```bash
cd /packages/cwf-hel-vite-vue3-demo-remote
pnpm build
pnpm preview
```

## cwf-hel-vite-vue3-demo-host

> 这个仓库用来演示 hel 对 vite 的支持程度有限，会导致页面报错加载不了

```bash
cd /packages/cwf-hel-vite-vue3-demo-host
pnpm dev
```

## cwf-hel-vite-vue3-demo-host-patch

> 这个仓库用来演示如何通过自定义个 parseHtml 的 custom api，规避 hel 对 vite 支持的称为

```bash
cd /packages/cwf-hel-vite-vue3-demo-host-patch
pnpm dev
```
