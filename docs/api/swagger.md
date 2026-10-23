# Swagger UI

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swagger-ui-dist@5.17.14/swagger-ui.css">
<div id="swagger-ui"></div>
<script src="https://cdn.jsdelivr.net/npm/swagger-ui-dist@5.17.14/swagger-ui-bundle.js"></script>
<script>
  window.addEventListener("load", function () {
    SwaggerUIBundle({ url: "../openapi.yaml", dom_id: "#swagger-ui", docExpansion: "full" });
  });
</script>
