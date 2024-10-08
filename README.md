# Back end project M1 ISEN

1. **`build`** :

    ```bash
    npm run build
    ```

    Cette commande compile le projet en TypeScript et génère les fichiers JavaScript dans le dossier `dist/`. C'est utile pour préparer l'application à être exécutée en production ou pour être déployée.

2. **`format`** :

    ```bash
    npm run format
    ```

    Utilise Prettier pour formater automatiquement tous les fichiers TypeScript dans les dossiers `src/` et `test/`. C'est utile pour s'assurer que le code respecte une convention de style uniforme.

3. **`start`** :

    ```bash
    npm start
    ```

    Démarre l'application NestJS en mode de production.

4. **`start:dev`** :

    ```bash
    npm run start:dev
    ```

    Démarre l'application en mode développement, avec la fonctionnalité de rechargement à chaud activée (`--watch`). Cela permet de redémarrer automatiquement l'application lorsque des modifications dans le code sont détectées.

5. **`start:debug`** :

    ```bash
    npm run start:debug
    ```

    Démarre l'application en mode de développement avec des options de débogage activées (`--debug --watch`). Cette commande permet d'inspecter l'application à l'aide d'outils de débogage tout en surveillant les changements de fichiers.

6. **`start:prod`** :

    ```bash
    npm run start:prod
    ```

    Exécute l'application directement depuis le dossier `dist/`, ce qui signifie qu'elle fonctionne avec le code compilé en production.

7. **`lint`** :

    ```bash
    npm run lint
    ```

    Utilise ESLint pour analyser et corriger automatiquement les fichiers TypeScript dans les répertoires `src`, `apps`, `libs` et `test`. C'est utile pour s'assurer que le code respecte les règles de style et de qualité définies.

8. **`test`** :

    ```bash
    npm run test
    ```

    Exécute les tests unitaires avec Jest. Cela lance tous les tests définis dans les fichiers `*.spec.ts`.

9. **`test:watch`** :

    ```bash
    npm run test:watch
    ```

    Exécute les tests avec Jest en mode surveillance, ce qui signifie qu'ils sont relancés automatiquement chaque fois que le code est modifié.

10. **`test:cov`** :

    ```bash
    npm run test:cov
    ```

    Exécute les tests unitaires et génère un rapport de couverture de code. Cela permet de vérifier quels pourcentages du code sont couverts par les tests.

11. **`test:debug`** :

    ```bash
    npm run test:debug
    ```

    Lance les tests avec Jest en mode débogage. Il utilise l'option `--inspect-brk` pour permettre de déboguer les tests à l'aide d'un outil comme Chrome DevTools ou VSCode.

12. **`test:e2e`** :

    ```bash
    npm run test:e2e
    ```

    Exécute les tests end-to-end (E2E) en utilisant Jest avec la configuration spécifiée dans `./test/jest-e2e.json`. Ces tests permettent de tester l'application dans son ensemble pour vérifier son bon fonctionnement global.
