Keystore :

keytool -genkey -alias sailpointattestation -keyalg RSA -keystore "C:\Users\rames\OneDrive\Desktop\SSO\sailpoint_keystore.jks"

keytool -export -alias sailpointattestation -file "C:\Users\rames\OneDrive\Desktop\SSO\sailpoint_public_cer.cer" -keystore "C:\Users\rames\OneDrive\Desktop\SSO\sailpoint_keystore.jks"