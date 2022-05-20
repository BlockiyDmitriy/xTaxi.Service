# xTaxi.Service
 
		<site name="xTaxi" id="2">
                <application path="/" applicationPool="Clr4IntegratedAppPool">
                    <virtualDirectory path="/" physicalPath="..\xTaxi.Service\xTaxi\xTaxi" />
                </application>
                <bindings>
                    <binding protocol="https" bindingInformation="*:44399:localhost" />
                    <binding protocol="http" bindingInformation="*:44399:localhost" />
                    <binding protocol="https" bindingInformation="*:44399:127.0.0.1" />
                    <binding protocol="http" bindingInformation="*:63268:127.0.0.1" />
                </bindings>
            </site>            