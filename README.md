# FaithFormationRegistrationPage Requested Changes

## Spanish Page
- At top, “Registro de Catecismo” and “clase de catecismo” // ~lines 2088 - 2089

```html
<div _ngcontent-rpt-c89="" fxlayout="column" fxflex="1 1 80%" fxflex.sm="1 1 80%" fxflex.xs="1 1 100%"
    style="flex-direction: column; box-sizing: border-box; display: flex; flex: 1 1 100%; max-width: 80%;">

    <mat-card-title _ngcontent-rpt-c89="" class="mat-card-title">Registro de catecismo</mat-card-title> <!--TODO: Changed from "Registro de formacion" to "Registro de catecismo"-->
    <mat-card-subtitle _ngcontent-rpt-c89="" class="mat-card-subtitle">Parroquia Sagrada Familia</mat-card-subtitle> <!--TODO: Changed from "Holy Family Parish" to "Parroquia Sagrada Familia"-->
</div>
```

- `Genero` drop-down items need to be updated:

```html
<div cdk-overlay-origin="" class="mat-select-trigger ng-tns-c106-8">
    <div class="mat-select-value ng-tns-c106-8" id="mat-select-value-3">
        <span class="mat-select-placeholder ng-tns-c106-8 ng-star-inserted">Genero</span>
        <!----><!---->
    </div>
    <div class="mat-select-arrow-wrapper ng-tns-c106-8"><div class="mat-select-arrow ng-tns-c106-8"></div></div> <!--TODO: This drop-down should display two options: "Femenino" & "Masculino". It currently displays "Masculino" & "Mujer"-->
</div>
```

- Correct checkbox label:

```html
<span class="mat-checkbox-label"><span style="display: none;">&nbsp;</span>¿es feligrés registrado?</span> <!--TODO: Updated text from "?esta feligrés?" to "¿es feligrés registrado?"-->
```

- Re-word `Household Information (Informacion del hogar)` section labels:
```html
<div _ngcontent-egv-c169="" class="mt-16" style="flex-direction: row; box-sizing: border-box; display: flex;">
    ...
    <mat-card-header _ngcontent-egv-c169="" class="mat-card-header">
        <div class="mat-card-header-text"><mat-card-title _ngcontent-egv-c169="" class="mat-card-title"> Información de la familia </mat-card-title></div> <!--TODO: "Informacion del hogar" changed to "Información de la familia"-->
    </mat-card-header>

    ...

    <span class="ng-tns-c70-9 ng-star-inserted">Apellido de la familia</span> <!--TODO: Changed "Appellido del hogar" with "Apellido de la familia"-->

    ...

    <span class="ng-tns-c70-17 ng-star-inserted">Número de telefono de la familia</span> <!--TODO: Changed "Numero de telefono del hogar" to "Número de telefono de la familia"-->

    ...

    <span class="ng-tns-c70-10 ng-star-inserted">Correo electrónico de la familia</span> <!--TODO: Changed "Correo electronico del hogar" to "Correo electrónico de la familia"-->

    ...
</div>


```