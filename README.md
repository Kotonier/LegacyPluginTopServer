# LegacyPluginTopServer

Veuillez utilise oxmysql afin de pouvoir faire les query mysql sinon, changer le MySQL.query en MySQL.Async.fetchAll

ajouter dans vote fxmanifest ces 2 lignes 

server_script '@oxmysql/lib/MySQL.lua'
shared_script '@es_extended/imports.lua'
