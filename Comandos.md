GET : quando quero perguntar algo

GET 



    Adicionadas as variaveis no arquivo `main` dentro bloco `common_env_vars`
    LOGGI_TEC_BANK_SLIP_ACC_AG_DIGIT: "{{ loggi_tec_bank_slip_acc_ag_digit }}"
    LOGGI_TEC_BANK_SLIP_AGENCY: "{{ loggi_tec_bank_slip_agency }}"
    LOGGI_TEC_BANK_SLIP_LOGGI_ACCOUNT: "{{ loggi_tec_bank_slip_loggi_account }}"
    LOGGI_TEC_BANK_SLIP_WALLET: "{{ loggi_tec_bank_slip_wallet }}"
    
    Adicionadas as variaveis no arquivos `secrets` ao fim do arquivo
    loggi_tec_bank_slip_acc_ag_digit
    loggi_tec_bank_slip_agency
    loggi_tec_bank_slip_loggi_account
    loggi_tec_bank_slip_wallet
    
    Valores Vault PRD : ^?https://vaultin.loggi.com/ui/vault/secrets/apps/show/loggiweb/external-secret-loggiweb
    - Variaveis nao disponiveis/cadastradas em STG