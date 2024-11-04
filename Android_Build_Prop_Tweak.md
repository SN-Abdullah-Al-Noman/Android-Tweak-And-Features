# Android-Tweak-And-Features:

Universal Build Prop Tweak:

01: Multi User: (system build.prop)
fw.max_users=5            
fw.show_multiuserui=1

# Samsung Build Prop Tweak:
01: Samsung Extra Dim: (system build.prop)
ro.surface_flinger.protected_contents=true

02 : S24 About Phone style (system build.prop)
ril.support.dynamic_imei=true

03: Galaxy Enhance X on unsupported device: (product build.prop)
ro.product.product.name=r0sxxx

# Fixes:
03: Remove ESIM option from settings:
Delete this file: privapp-permissions-com.samsung.euicc.xml             
From:
system/etc/permissions folder.
