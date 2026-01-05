# 🎙️ an8nymous TTS

**Clonagem de Voz com Inteligência Artificial** - Clone qualquer voz com apenas 6-10 segundos de áudio!

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/an8nymous0/an8nymous-chatterbox-colab/blob/main/an8nymous_TTS.ipynb)

---

## 🚀 Como Usar

1. Clique no botão **"Open in Colab"** acima
2. Clique no ▶️ (play) para executar
3. Autorize o acesso ao **Google Drive** (para cache persistente)
4. Aguarde a inicialização:
   - **1ª execução**: ~3-5 minutos (instalação + download do modelo)
   - **Próximas execuções**: ~30 segundos (cache!)
5. Use a **URL pública** gerada para acessar de qualquer lugar!

---

## ✨ Funcionalidades

- 🎤 **Clonagem de Voz** - Clone qualquer voz com 6-10 segundos de áudio
- 🌍 **23 Idiomas** - Português, Inglês, Espanhol, Francês, e mais
- 🔄 **Cross-Language** - Clone uma voz e fale em outro idioma
- ⚡ **GPU Gratuita** - Roda no Google Colab (T4 GPU)
- 🔗 **URL Pública** - Acesse de qualquer dispositivo
- 💾 **Cache Persistente** - Google Drive salva modelo e dependências

---

## 💾 Sistema de Cache

O notebook usa seu **Google Drive** para cachear:

| Item | Tamanho | Local |
|------|---------|-------|
| Modelo TTS | ~2 GB | `/MyDrive/an8nymous_tts_cache/models/` |
| Dependências pip | ~500 MB | `/MyDrive/an8nymous_tts_cache/deps/` |
| Repositório | ~50 MB | `/MyDrive/an8nymous_tts_cache/chatterbox_repo/` |

**Benefícios:**
- Execuções subsequentes carregam em ~30 segundos
- Não precisa reinstalar dependências
- Modelo fica salvo no seu Drive
- Keep-alive automático (previne desconexão por inatividade)

**Para limpar o cache:** Delete a pasta `an8nymous_tts_cache` no seu Google Drive.

---

## 🌍 Idiomas Suportados

| Idioma | Código | Idioma | Código |
|--------|--------|--------|--------|
| Português | pt | Inglês | en |
| Espanhol | es | Francês | fr |
| Alemão | de | Italiano | it |
| Japonês | ja | Chinês | zh |
| Coreano | ko | Russo | ru |
| Árabe | ar | Hindi | hi |
| Holandês | nl | Polonês | pl |
| Turco | tr | Sueco | sv |
| Dinamarquês | da | Norueguês | no |
| Finlandês | fi | Grego | el |
| Hebraico | he | Malaio | ms |
| Suaíli | sw | | |

---

## 📝 Parâmetros

| Parâmetro | Descrição | Valor Padrão |
|-----------|-----------|--------------|
| Expressividade | Intensidade emocional (0.25-2.0) | 0.5 |
| Temperatura | Variação na geração | 0.8 |
| CFG/Ritmo | Controle de ritmo | 0.5 |
| Seed | Reprodutibilidade (0 = aleatório) | 0 |

---

## ⚠️ Uso Responsável

- **Não clone vozes sem autorização** do dono da voz
- Use apenas para fins legítimos e éticos
- Respeite direitos autorais e de imagem

---

## 🙏 Créditos

- **Chatterbox TTS**: [Resemble AI](https://github.com/resemble-ai/chatterbox)
- **Adaptação Multilingual**: [NeuralFalconYT](https://github.com/NeuralFalconYT/Chatterbox-Multilingual)
- **Customização**: [an8nymous](https://github.com/an8nymous0)

---

## 📄 Licença

Este projeto utiliza o Chatterbox TTS sob licença MIT.
