# mikrotik-routeros7-rancid-cvsweb
rancid.types.conf for mikrotik routeros (ros) version 7 (ros7)

mikrotik7;script;rancid -t mikrotik7

mikrotik7;login;mtlogin

mikrotik7;module;routeros

mikrotik7;inloop;routeros::inloop

mikrotik7;command;routeros::SystemPackagePrintDetail;system package print detail without-paging

mikrotik7;command;routeros::SystemRouterboardPrint;system routerboard print

mikrotik7;command;routeros::SystemLicensePrint;system license print

mikrotik7;command;routeros::Export;export terse show-sensitive
