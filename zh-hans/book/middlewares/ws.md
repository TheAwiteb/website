# WebSocket

提供对 `WebSocket` 支持的中间件.

## 配置 Cargo.toml

```toml
salvo = { version = "*", features = ["ws"] }
```

## 示例代码

<CodeGroup>
<CodeGroupItem title="main.rs" active>

@[code rust](../../../codes/ws/src/main.rs)

</CodeGroupItem>
<CodeGroupItem title="Cargo.toml">

@[code toml](../../../codes/ws/Cargo.toml)

</CodeGroupItem>
</CodeGroup>

### 聊天程序示例

<CodeGroup>
<CodeGroupItem title="main.rs" active>

@[code rust](../../../codes/ws-chat/src/main.rs)

</CodeGroupItem>
<CodeGroupItem title="Cargo.toml">

@[code toml](../../../codes/ws-chat/Cargo.toml)

</CodeGroupItem>
</CodeGroup>