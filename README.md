# Firmware1_18
# Madre : Firmware 1_17
# Para  : solutions.fusepong.com
#
# Generador de pines
# Comunicacion entre dispositivos
# Actualizador
# horarios
# Mejoras visualizacion estados
# Seguridad con switch fisico
# Mejoras modulo ethernet Filtro de errores
# Menu configuracion test ingreso nuevo Dominio
# Restablecimeinto automatico por perdida de server y dominio
# Invitaciones
# Unificacion para dispositivos CAT01 y CAE01
# sin restablecimiento
# modificaion formato tipo 1 impreso.


5Jmo57DBNSsRkddsJA/oCInKdaB39i+0JUOIfgX93Enp5M6Gh5XCbGes06Ri1r8RhDfoLGvLBSxljwy1c/+Mbg==.h17dm.1666991805.1666999005.11568

3.DbxNa6ByqpAy4qd2Kj1qoQ==.DziKVGtThkNGlXjrb20a1g==.1.1666994280000



Error :500
{"errors":[{"status":500,"source":{"pointer":"http://35.88.204.191/api/access/get_granted_invitations_pi"},"title":"PG::UndefinedColumn: ERROR:  column invited_clients.state does not exist\nLINE 1: ...s\" WHERE \"invited_clients\".\"location_id\" = $1 AND \"invited_c...\n                                                             ^\n: SELECT \"invited_clients\".* FROM \"invited_clients\" WHERE \"invited_clients\".\"location_id\" = $1 AND \"invited_clients\".\"state\" IN ($2, $3)","details":["/home/sportlife_b/Fusepong-Solutions-Back/app/controllers/api/v1/access_controller.rb:1971:in `map'","/home/sportlife_b/Fusepong-Solutions-Back/app/controllers/api/v1/access_controller.rb:1971:in `block in get_granted_invitations_pi'","/home/sportlife_b/Fusepong-Solutions-Back/app/controllers/api/v1/access_controller.rb:1962:in `get_granted_invitations_pi'"]}]}
Error :500