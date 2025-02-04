---
uid: mvc/overview/older-versions/getting-started-with-ef-5-using-mvc-4/building-the-ef5-mvc4-chapter-downloads
title: "Building the Chapter Downloads for the EF 5 MVC 4 Tutorials | Microsoft Docs"
author: Rick-Anderson
description: "The Contoso University sample web application demonstrates how to create ASP.NET MVC 4 applications using the Entity Framework 5 Code First and Visual Studio..."
ms.author: riande
ms.date: 04/20/2022
ms.custom: devdivchpfy22
ms.assetid: d0a89089-eed8-4f61-a478-c5ffa30186f5
msc.legacyurl: /mvc/overview/older-versions/getting-started-with-ef-5-using-mvc-4/building-the-ef5-mvc4-chapter-downloads
msc.type: authoredcontent
---
# Building the Chapter Downloads for the EF 5 MVC 4 Tutorials

by [Rick Anderson](https://twitter.com/RickAndMSFT)

> The Contoso University sample web application demonstrates how to create ASP.NET MVC 4 applications using the Entity Framework 5 Code First and Visual Studio 2012. For information about the tutorial series, see [the first tutorial in the series](creating-an-entity-framework-data-model-for-an-asp-net-mvc-application.md).

## Building the Chapter Downloads

1. Download and unzip the  project sample zip file. In the unzipped download package, you will find additional zip files, one for the completion of each chapter.
2. Right click on the desired zip file, click **Properties**, and click the **Unblock** button.  
  
    :::image type="content" source="building-the-ef5-mvc4-chapter-downloads/_static/image1.png" alt-text="Screenshot of the Properties window.":::

3. Unzip the file.
4. Double-click the *CUx.sln* file to launch Visual Studio.
5. From the **Tools** menu, click **NuGet Package Manager**, then **Package Manager Console**.  
  
    :::image type="content" source="building-the-ef5-mvc4-chapter-downloads/_static/image2.png" alt-text="Screenshot of the Package Manager Console window.":::

6. In the Package Manager Console (PMC), click **Restore**.  
  
    :::image type="content" source="building-the-ef5-mvc4-chapter-downloads/_static/image3.png" alt-text="Screenshot of restoring Visual Studio.":::

7. Exit Visual Studio.
8. Restart Visual Studio, opening the solution file you closed in the step above.
9. In the Package Manager Console (PMC), enter the `Update-Database` command:  
  
    :::image type="content" source="building-the-ef5-mvc4-chapter-downloads/_static/image4.png" alt-text="Screenshot of the Update Database command.":::  

    > [!NOTE]
    > If you get the following error:  
    >   
    >  *The term 'Update-Database' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a path was included, verify that the path is correct and try again.*  
    > Exit and restart Visual Studio.

    Each migration will run, then the seed method will run. You can now run the app.

    :::image type="content" source="building-the-ef5-mvc4-chapter-downloads/_static/image5.png" alt-text="Screenshot of running the app.":::

> [!div class="step-by-step"]
> [Previous](advanced-entity-framework-scenarios-for-an-mvc-web-application.md)
