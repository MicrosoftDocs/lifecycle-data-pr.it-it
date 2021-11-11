---
title: Guida all'esportazione dei dati del ciclo di vita
description: Guida all'esportazione delle informazioni sul ciclo di vita del prodotto
ms.date: 12/16/2020
layout: ContentPage
ms.openlocfilehash: 5e9dddbff5fac32e6d3cf8ef0943151d2dfe5e35
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 11/02/2021
ms.locfileid: "3546860"
---
# <a name="lifecycle-data-export-guidance"></a>Guida all'esportazione dei dati del ciclo di vita
In questo documento viene descritto come utilizzare il file di esportazione del prodotto.

## <a name="query-information"></a>Informazioni sulle query
Nel documento Excel sono disponibili campi che consentono di identificare i dati inseriti nella tabella dei prodotti.

### <a name="end-of-support"></a>Fine del supporto
Il valore di fine del supporto filtrerà i prodotti in base alla data di fine del supporto del prodotto o alle date di fine del rilascio.

Valori possibili: tutti (nessun filtro applicato), anno e intervallo.

### <a name="family"></a>Famiglia
Il valore della famiglia filtra i prodotti in base al loro livello genitore all'interno della gerarchia nota come famiglia.

Valori possibili: tutti (nessun filtro applicato), nome famiglia

### <a name="group"></a>Gruppo
Il valore del gruppo filtra i prodotti appartenenti al loro livello genitore (famiglia) in un gruppo specifico.

Valori possibili: tutti (nessun filtro applicato), nome gruppo

## <a name="table-columns"></a>Colonne della tabella
La tabella dei prodotti è composta da colonne che definiscono il prodotto, le edizioni, le versioni e le date di supporto corrispondenti.

> [!NOTE]
> Per ogni combinazione di prodotto, edizione e versione ci sarà una riga.

### <a name="product"></a>Prodotto
Nome del prodotto.

### <a name="edition"></a>Edition
La colonna dell'edizione verrà popolata quando il prodotto contiene le edizioni. Se non è disponibile alcuna edizione del prodotto, questo campo sarà vuoto.

### <a name="release"></a>Rilascia
La colonna versione verrà popolata quando il prodotto contiene più versioni.
Quando il prodotto ha una sola versione, questo campo sarà vuoto.

### <a name="support-policy"></a>Criteri di supporto
Questo campo definisce il criterio di supporto seguito dal prodotto.

Valori possibili: [fissi](/lifecycle/policies/fixed), [moderni](/lifecycle/policies/modern), componente

### <a name="start-date"></a>Data inizio
Data di inizio del supporto per il prodotto.

### <a name="mainstream-date"></a>Data Mainstream
Quando i criteri di supporto sonno **fissi** o relativi ai **componenti**, questa è la data di fine del supporto Mainstream del prodotto.
  
Quando i criteri di supporto sono **moderni**, questo campo sarà vuoto.

### <a name="extended-end-date"></a>Data di fine del supporto Extended
Quando i criteri di supporto sono **fissi** o relativi ai **componenti**, questa è la data di fine del supporto Extended del prodotto.

Quando i criteri di supporto sono **moderni**, questo campo sarà vuoto.

### <a name="retirement-date"></a>Data del ritiro
Quando i criteri di supporto sono **fissi** o relativi ai **componenti**, questo campo sarà vuoto.

Quando i criteri di supporto sono **moderni**, questa sarà la data di ritiro del prodotto.

### <a name="release-start-date"></a>Data di inizio della versione
Data di inizio del supporto per la versione. Quando il prodotto ha una sola versione, questo campo sarà vuoto.
 
### <a name="release-end-date"></a>Data di fine della versione
Data di fine del supporto per la versione.
Quando il prodotto ha una sola versione, questo campo sarà vuoto.

### <a name="docs-url"></a>URL documenti
URL della documentazione estesa.
