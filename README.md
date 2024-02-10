class inimigo {
    constructor(nome,tipo,PontosDeVida)
    {
        this.nome=nome;
        this.tipo=tipo;
        this.PontosDeVida;
        AbstractRange(alvo)
        let dano= math.floor(math.random()*10)+1;
        alvo.PontosDeVida-=dano;
        console.log(this.nome+"atacou"+alvo.nome+"e causou"+dano+"de dano");
    }
    receberDano(dano){
        this.PontosDeVida-=dano;
        console.log(this.nome+"recebeu"+dano+"de dano");
        if(this.PontosDeVida<=0)
            console.log(this.nome+"morreu");
        

    }

    }
}
