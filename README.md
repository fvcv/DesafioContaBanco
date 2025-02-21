class ContaBancaria:
    def_init_(self,usuario):
    self.usuario = usuario
    self.saldo = 0.0
    self.extrato = [ ]
    self.saques_diarios = 0
    self.limite_saque_valor = 500.0
        def depositar(self, valor):
            if valor > 0:
            self.saldo += valor
            self.extrato.append(f" Deposito: R$ {valor:.2f}")
                print (f" Deposito de R$ {valor:.2f} realizado com sucesso! ")
                    else:
                        print("Valor inválido para deposito.")

                            def sacar(self, valor):
                                if self.saques_diarios >= self.limite_saques;
                                    print("Limite de saques diários atingido! ")
                                        elif valor > self.limite_saque_valor:
                                            print(f" O valor máximo para saque é R$ {self.limite_saque_valor:.2f}.")
                                                elif valor > self.saldo:
                                                    print("Saldo insuficiente para saque. ")
                                                        elif valor > 0:
                                                            self.saldo -= valor
                                                            self.extrato.append(f"Saque: R$ {valor:.2f}")
                                                            self.saques_diarios += 1
                                                               print(f"saque de R$ {valor:.2f}.realizado com sucesso!")
                                                                   else:
                                                                       print("Valor inválido para saque. ")
                                                                           def exibir_extrato(self):
                                                                               print("\nExtrato da Conta: ")
                                                                                   for transacao in self.extrato:
                                                                                       print(transacao)
                                                                                       print(f"Saldo atual: R$ {self.saldo:.2f}\n")
                                                                                           def resetar_saques_diarios(self):
                                                                                               self.saques_diarios = 0
                                                                                                   print("Limite de saques diários resetado. ")
                                                                                                   
                                                                                   
                                                                           

                    
                          
