<apex:page controller="ImobiliariaController">
    <Style>
        
        #conteudo{
        margin-top:10%;    
        margin-left:10%;    
        margin-right:10%;    
        }
        
        #form1{ 
        width:300px;
        }
    
    </Style>

    <div id="conteudo">
        <center>
            <div id="form1">
                <apex:form >   
                    <apex:pageBlock title="Cadastrar imoveis">             
                        <apex:panelGrid columns="2">
                            
                            Quartos: <apex:inputText value="{!Quartos}"/>   
                            Banheiros: <apex:inputText value="{!Banheiros}"/>   
                            sala: <apex:inputText value="{!Sala}"/> 
                            Cozinha: <apex:inputText value="{!Cozinha}"/>   
                            Suíte: <apex:inputText value="{!Suite}"/>   
                            Garagem: <apex:inputText value="{!Vagas}"/> 
                            valor: <apex:inputText value="{!valor}"/>   
                        </apex:panelGrid>
                        <br/>
                        <apex:commandButton value="SALVAR" action="{!salvarImoveis}"/>;
                        
                        
                    </apex:pageBlock>       
                </apex:form>    
                
            </div> 
        </center>
    </div>    
</apex:page>
