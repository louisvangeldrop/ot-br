Gebruik deze folder voor de ESP32C5 OTBR 
See: https://github.com/espressif/esp-thread-br/issues/168

VSCode  C:\Users\louis\projecten\esp\esp-thread-br\examples\basic_thread_border_router
Copy partiions.csv en sdkconfig.defaults.esp32c5
Open IDF Terminal
idf.py set-target ESP32C5
Build
Flash

Door een wijziging in ot-br kun je niet meer je eigen dataset invoeren. Via web-gui form Network. 
wel via ot dataset pskc 445f2b5ca6f2a93a55ce570a70efeecb   de key invoeren