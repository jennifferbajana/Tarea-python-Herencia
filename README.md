# Tarea-python-Herencia
Herencia-cuentas 
#BAJAÑA TARIRA JENNIFFER TATIANA
class cuenta:
    def __init__ (self, numero, nombrePropietario, saldo,):
        cuenta.contador_cuenta += 1
        self._numero = numero
        self._nombrePropietario = nombrePropietario
        self._saldo = saldo

    def __str__(self) -> str:
        return f' cuenta [numero: {self._numero}, nombrePropietario: {self._nombrePropietario}, saldo: {self._saldo}]'
    @property
    def numero(self):
        return self._numero
    @numero.setter
    def numero(self, numero):
        self ._numero = numero
    @property
    def nombrePropietario(self):
        return self._nombrePropietario
    @nombrePropietario.setter
    def nombrePropietario(self, nombrePropietario):
        self ._nombrePropietario= nombrePropietario

    @property
    def saldo(self):
        return self._saldo
    @saldo.setter
    def saldo(self, saldo):
        self ._saldo = saldo


cuenta = input('Favor indique numero de cuenta: ')
nombrePropietario = input(str('Ingrese el propietario: '))
ctaahorro = int(input('Favor Ingrese saldo anterior: '))
deposito = int (input ('Ingrese monto a depositar: '))
sum = ctaahorro + deposito
print('El saldo de su cuenta es: ', sum)

#BAJAÑA TARIRA JENNIFFER TATIANA
class cuentaCorriente:
    def __init__ (self, credito, debito, mostrar, pagar_cheque,):
        cuentaCorriente.contador_cuenta_ahorro += 1
        self._credito = credito
        self._debito = debito
        self._mostrar = mostrar
        self._pagar_cheque = pagar_cheque

    def __bool__(self) -> bool:
        return f' cuentaCorriente [credito: {self._credito}, debito: {self._debito}, mostrar: {self._mostrar}, pagar_cheque: {self._pagar_cheque}]'
    @property
    def credito(self):
        return self._credito
    @credito.setter
    def credito(self, credito):
        self ._credito = credito
    @property
    def debito(self):
        return self._debito
    @debito.setter
    def debito(self, debito):
        self ._debito = debito
    @property
    def mostrar(self):
        return self._mostrar
    @mostrar.setter
    def mostrar(self, mostrar):
        self ._mostrar = mostrar
    @property
    def pagar_cheque(self):
        return self._pagar_cheque

    @pagar_cheque.setter
    def pagar_cheque(self, pagar_cheque):
        self._pagar_cheque = pagar_cheque

cuentaCorriente = input('Favor indique numero de cuenta: ')
Propietario = input(str('Ingrese el propietario: '))
ctacorriente = int(input('Favor Ingrese saldo anterior: '))
retiro = int (input ('Ingrese monto a retirar: '))
res = ctacorriente - retiro
print('El saldo de su cuenta es: ', res)



#BAJAÑA TARIRA JENNIFFER TATIANA
class cuenta_ahorro:
    def __init__ (self, interes, credito, debito, mostrar, pagar_interes,):
        cuenta_ahorro.contador_cuenta_ahorro += 1
        self._interes = interes
        self._credito = credito
        self._debito = debito
        self._mostrar = mostrar
        self._pagar_interes = pagar_interes

    def __float__(self) -> float:
        return f' cuenta_ahorro [interes:{self._interes}, credito: {self._credito}, debito: {self._debito}, mostrar: {self._mostrar}, pagar_interes: {self._pagar_interes}]'

    @property
    def interes(self):
        return self._interes

    @interes.setter
    def interes(self, interes):
        self._interes = interes
    @property
    def credito(self):
        return self._credito

    @credito.setter
    def credito(self, credito):
        self ._credito = credito

    @property
    def debito(self):
        return self._debito

    @debito.setter
    def debito(self, debito):
        self ._debito = debito

    @property
    def mostrar(self):
        return self._mostrar
    @mostrar.setter
    def mostrar(self, mostrar):
        self ._mostrar = mostrar

    @property
    def pagar_interes(self):
        return self._pagar_interes
    @pagar_interes.setter
    def pagar_interes(self, pagar_interes):
        self._pagar_interes = pagar_interes



cuenta_ahorro= input('Favor indique numero de cuenta: ')
Propietario = input(str('Ingrese el propietario: '))
ctaahorro = int(input('Favor Ingrese saldo anterior: '))
deposito = int (input ('Ingrese monto a depositar: '))
sum = ctaahorro + deposito
print('El saldo de su cuenta es: ', sum)

