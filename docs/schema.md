curl --request PUT \
 --url https://ciper.vtexcommercestable.com.br/api/dataentities/CT/schemas/contact \
 --header 'Content-Type: application/json' \
 --header 'X-VTEX-API-AppKey: vtexappkey-ciper-BLPCPS' \
 --header 'X-VTEX-API-AppToken: HIVGCYBFAIIJLDRVYXKCOWWJAQIWWVBNHGUJCTMEETLYQKJLEEAXBNRLLMGMPFIFHVCEIHTFKGXVKXTPGWRSUELTPJYPNAOZKGRUIFDWKVMVPVANTQFSNQKDKIOZJDRJ'
--data '{"title":"customer-contact","type":"object","properties":{"email":{"type":"string","format":"email","title":"Correo"},"name":{"type":"string","maxLength":100,"title":"Nombre"},"message":{"type":"string","title":"Comentario"},"phone":{"type":"string","maxLength":50,"title":"Teléfono"},"subject":{"type":"string","title":"Tipo Consulta","enum":["Dudasyconsultas","Postventa","Reclamos"]}},"requeried":["email","name","message","phone","subject"],"v-indexed":["email"],"v-security":{"publicJsonSchema":true,"allowGetAll":true}}'
