# GECE - Releases

Repositório oficial de distribuição de versões do **GECE** (Gestão de Certificados e Estudantes), aplicação desktop para emissão e gestão de certificados académicos.

## Download

Aceda à [página de releases](../../releases) e baixe o instalador correspondente ao seu sistema operativo.

| Plataforma | Arquivo              | Arquitectura     |
| ---------- | -------------------- | ---------------- |
| Windows    | `GECE-x.x.x.exe`    | x64              |
| macOS      | `GECE-x.x.x.dmg`    | x64 / Apple Silicon |
| Linux      | `GECE-x.x.x.AppImage` / `.deb` | x64  |

## Requisitos do sistema

| Plataforma | Versão mínima         |
| ---------- | --------------------- |
| Windows    | Windows 10 (64-bit)   |
| macOS      | macOS 11 Big Sur      |
| Linux      | Ubuntu 20.04 / equivalente |

## Instalação

### Windows

1. Baixe o ficheiro `.exe`.
2. Execute o instalador e siga os passos do assistente.
3. O atalho **GECE** será criado no ambiente de trabalho e no menu Iniciar.

### macOS

1. Baixe o ficheiro `.dmg`.
2. Abra o `.dmg` e arraste o ícone do GECE para a pasta **Aplicações**.
3. Na primeira execução, clique com o botão direito → **Abrir** (necessário por ser de um desenvolvedor não verificado pela Apple).

### Linux

**AppImage**
```bash
chmod +x GECE-x.x.x.AppImage
./GECE-x.x.x.AppImage
```

**Debian / Ubuntu (.deb)**
```bash
sudo dpkg -i GECE-x.x.x.deb
```

## Actualizações automáticas

A aplicação verifica automaticamente a existência de novas versões ao iniciar. Quando uma actualização estiver disponível, será notificado e poderá instalá-la directamente pela aplicação.

> As actualizações automáticas estão disponíveis apenas no **Windows** e **macOS**.  
> No **Linux**, baixe e reinstale manualmente a partir desta página.

## Suporte

- Site: [gece.ao](https://gece.ao)
- Email: [geral@gece.ao](mailto:geral@gece.ao)
