---
permalink: /v6.0.0/job/v1alpha1/minIOJob/
---

# job.v1alpha1.minIOJob



## Index

* [`fn new(name)`](#fn-new)
* [`obj metadata`](#obj-metadata)
  * [`fn withAnnotations(annotations)`](#fn-metadatawithannotations)
  * [`fn withAnnotationsMixin(annotations)`](#fn-metadatawithannotationsmixin)
  * [`fn withClusterName(clusterName)`](#fn-metadatawithclustername)
  * [`fn withCreationTimestamp(creationTimestamp)`](#fn-metadatawithcreationtimestamp)
  * [`fn withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)`](#fn-metadatawithdeletiongraceperiodseconds)
  * [`fn withDeletionTimestamp(deletionTimestamp)`](#fn-metadatawithdeletiontimestamp)
  * [`fn withFinalizers(finalizers)`](#fn-metadatawithfinalizers)
  * [`fn withFinalizersMixin(finalizers)`](#fn-metadatawithfinalizersmixin)
  * [`fn withGenerateName(generateName)`](#fn-metadatawithgeneratename)
  * [`fn withGeneration(generation)`](#fn-metadatawithgeneration)
  * [`fn withLabels(labels)`](#fn-metadatawithlabels)
  * [`fn withLabelsMixin(labels)`](#fn-metadatawithlabelsmixin)
  * [`fn withName(name)`](#fn-metadatawithname)
  * [`fn withNamespace(namespace)`](#fn-metadatawithnamespace)
  * [`fn withOwnerReferences(ownerReferences)`](#fn-metadatawithownerreferences)
  * [`fn withOwnerReferencesMixin(ownerReferences)`](#fn-metadatawithownerreferencesmixin)
  * [`fn withResourceVersion(resourceVersion)`](#fn-metadatawithresourceversion)
  * [`fn withSelfLink(selfLink)`](#fn-metadatawithselflink)
  * [`fn withUid(uid)`](#fn-metadatawithuid)
* [`obj spec`](#obj-spec)
  * [`fn withCommands(commands)`](#fn-specwithcommands)
  * [`fn withCommandsMixin(commands)`](#fn-specwithcommandsmixin)
  * [`fn withExecution(execution)`](#fn-specwithexecution)
  * [`fn withFailureStrategy(failureStrategy)`](#fn-specwithfailurestrategy)
  * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-specwithimagepullpolicy)
  * [`fn withImagePullSecret(imagePullSecret)`](#fn-specwithimagepullsecret)
  * [`fn withImagePullSecretMixin(imagePullSecret)`](#fn-specwithimagepullsecretmixin)
  * [`fn withMcImage(mcImage)`](#fn-specwithmcimage)
  * [`fn withServiceAccountName(serviceAccountName)`](#fn-specwithserviceaccountname)
  * [`obj spec.commands`](#obj-speccommands)
    * [`fn withArgs(args)`](#fn-speccommandswithargs)
    * [`fn withArgsMixin(args)`](#fn-speccommandswithargsmixin)
    * [`fn withCommand(command)`](#fn-speccommandswithcommand)
    * [`fn withCommandMixin(command)`](#fn-speccommandswithcommandmixin)
    * [`fn withDependsOn(dependsOn)`](#fn-speccommandswithdependson)
    * [`fn withDependsOnMixin(dependsOn)`](#fn-speccommandswithdependsonmixin)
    * [`fn withEnv(env)`](#fn-speccommandswithenv)
    * [`fn withEnvFrom(envFrom)`](#fn-speccommandswithenvfrom)
    * [`fn withEnvFromMixin(envFrom)`](#fn-speccommandswithenvfrommixin)
    * [`fn withEnvMixin(env)`](#fn-speccommandswithenvmixin)
    * [`fn withName(name)`](#fn-speccommandswithname)
    * [`fn withOp(op)`](#fn-speccommandswithop)
    * [`fn withVolumeMounts(volumeMounts)`](#fn-speccommandswithvolumemounts)
    * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-speccommandswithvolumemountsmixin)
    * [`fn withVolumes(volumes)`](#fn-speccommandswithvolumes)
    * [`fn withVolumesMixin(volumes)`](#fn-speccommandswithvolumesmixin)
    * [`obj spec.commands.env`](#obj-speccommandsenv)
      * [`fn withName(name)`](#fn-speccommandsenvwithname)
      * [`fn withValue(value)`](#fn-speccommandsenvwithvalue)
      * [`obj spec.commands.env.valueFrom`](#obj-speccommandsenvvaluefrom)
        * [`obj spec.commands.env.valueFrom.configMapKeyRef`](#obj-speccommandsenvvaluefromconfigmapkeyref)
          * [`fn withKey(key)`](#fn-speccommandsenvvaluefromconfigmapkeyrefwithkey)
          * [`fn withName(name)`](#fn-speccommandsenvvaluefromconfigmapkeyrefwithname)
          * [`fn withOptional(optional)`](#fn-speccommandsenvvaluefromconfigmapkeyrefwithoptional)
        * [`obj spec.commands.env.valueFrom.fieldRef`](#obj-speccommandsenvvaluefromfieldref)
          * [`fn withApiVersion(apiVersion)`](#fn-speccommandsenvvaluefromfieldrefwithapiversion)
          * [`fn withFieldPath(fieldPath)`](#fn-speccommandsenvvaluefromfieldrefwithfieldpath)
        * [`obj spec.commands.env.valueFrom.resourceFieldRef`](#obj-speccommandsenvvaluefromresourcefieldref)
          * [`fn withContainerName(containerName)`](#fn-speccommandsenvvaluefromresourcefieldrefwithcontainername)
          * [`fn withDivisor(divisor)`](#fn-speccommandsenvvaluefromresourcefieldrefwithdivisor)
          * [`fn withResource(resource)`](#fn-speccommandsenvvaluefromresourcefieldrefwithresource)
        * [`obj spec.commands.env.valueFrom.secretKeyRef`](#obj-speccommandsenvvaluefromsecretkeyref)
          * [`fn withKey(key)`](#fn-speccommandsenvvaluefromsecretkeyrefwithkey)
          * [`fn withName(name)`](#fn-speccommandsenvvaluefromsecretkeyrefwithname)
          * [`fn withOptional(optional)`](#fn-speccommandsenvvaluefromsecretkeyrefwithoptional)
    * [`obj spec.commands.envFrom`](#obj-speccommandsenvfrom)
      * [`fn withPrefix(prefix)`](#fn-speccommandsenvfromwithprefix)
      * [`obj spec.commands.envFrom.configMapRef`](#obj-speccommandsenvfromconfigmapref)
        * [`fn withName(name)`](#fn-speccommandsenvfromconfigmaprefwithname)
        * [`fn withOptional(optional)`](#fn-speccommandsenvfromconfigmaprefwithoptional)
      * [`obj spec.commands.envFrom.secretRef`](#obj-speccommandsenvfromsecretref)
        * [`fn withName(name)`](#fn-speccommandsenvfromsecretrefwithname)
        * [`fn withOptional(optional)`](#fn-speccommandsenvfromsecretrefwithoptional)
    * [`obj spec.commands.resources`](#obj-speccommandsresources)
      * [`fn withClaims(claims)`](#fn-speccommandsresourceswithclaims)
      * [`fn withClaimsMixin(claims)`](#fn-speccommandsresourceswithclaimsmixin)
      * [`fn withLimits(limits)`](#fn-speccommandsresourceswithlimits)
      * [`fn withLimitsMixin(limits)`](#fn-speccommandsresourceswithlimitsmixin)
      * [`fn withRequests(requests)`](#fn-speccommandsresourceswithrequests)
      * [`fn withRequestsMixin(requests)`](#fn-speccommandsresourceswithrequestsmixin)
      * [`obj spec.commands.resources.claims`](#obj-speccommandsresourcesclaims)
        * [`fn withName(name)`](#fn-speccommandsresourcesclaimswithname)
    * [`obj spec.commands.volumeMounts`](#obj-speccommandsvolumemounts)
      * [`fn withMountPath(mountPath)`](#fn-speccommandsvolumemountswithmountpath)
      * [`fn withMountPropagation(mountPropagation)`](#fn-speccommandsvolumemountswithmountpropagation)
      * [`fn withName(name)`](#fn-speccommandsvolumemountswithname)
      * [`fn withReadOnly(readOnly)`](#fn-speccommandsvolumemountswithreadonly)
      * [`fn withRecursiveReadOnly(recursiveReadOnly)`](#fn-speccommandsvolumemountswithrecursivereadonly)
      * [`fn withSubPath(subPath)`](#fn-speccommandsvolumemountswithsubpath)
      * [`fn withSubPathExpr(subPathExpr)`](#fn-speccommandsvolumemountswithsubpathexpr)
    * [`obj spec.commands.volumes`](#obj-speccommandsvolumes)
      * [`fn withName(name)`](#fn-speccommandsvolumeswithname)
      * [`obj spec.commands.volumes.awsElasticBlockStore`](#obj-speccommandsvolumesawselasticblockstore)
        * [`fn withFsType(fsType)`](#fn-speccommandsvolumesawselasticblockstorewithfstype)
        * [`fn withPartition(partition)`](#fn-speccommandsvolumesawselasticblockstorewithpartition)
        * [`fn withReadOnly(readOnly)`](#fn-speccommandsvolumesawselasticblockstorewithreadonly)
        * [`fn withVolumeID(volumeID)`](#fn-speccommandsvolumesawselasticblockstorewithvolumeid)
      * [`obj spec.commands.volumes.azureDisk`](#obj-speccommandsvolumesazuredisk)
        * [`fn withCachingMode(cachingMode)`](#fn-speccommandsvolumesazurediskwithcachingmode)
        * [`fn withDiskName(diskName)`](#fn-speccommandsvolumesazurediskwithdiskname)
        * [`fn withDiskURI(diskURI)`](#fn-speccommandsvolumesazurediskwithdiskuri)
        * [`fn withFsType(fsType)`](#fn-speccommandsvolumesazurediskwithfstype)
        * [`fn withKind(kind)`](#fn-speccommandsvolumesazurediskwithkind)
        * [`fn withReadOnly(readOnly)`](#fn-speccommandsvolumesazurediskwithreadonly)
      * [`obj spec.commands.volumes.azureFile`](#obj-speccommandsvolumesazurefile)
        * [`fn withReadOnly(readOnly)`](#fn-speccommandsvolumesazurefilewithreadonly)
        * [`fn withSecretName(secretName)`](#fn-speccommandsvolumesazurefilewithsecretname)
        * [`fn withShareName(shareName)`](#fn-speccommandsvolumesazurefilewithsharename)
      * [`obj spec.commands.volumes.cephfs`](#obj-speccommandsvolumescephfs)
        * [`fn withMonitors(monitors)`](#fn-speccommandsvolumescephfswithmonitors)
        * [`fn withMonitorsMixin(monitors)`](#fn-speccommandsvolumescephfswithmonitorsmixin)
        * [`fn withPath(path)`](#fn-speccommandsvolumescephfswithpath)
        * [`fn withReadOnly(readOnly)`](#fn-speccommandsvolumescephfswithreadonly)
        * [`fn withSecretFile(secretFile)`](#fn-speccommandsvolumescephfswithsecretfile)
        * [`fn withUser(user)`](#fn-speccommandsvolumescephfswithuser)
        * [`obj spec.commands.volumes.cephfs.secretRef`](#obj-speccommandsvolumescephfssecretref)
          * [`fn withName(name)`](#fn-speccommandsvolumescephfssecretrefwithname)
      * [`obj spec.commands.volumes.cinder`](#obj-speccommandsvolumescinder)
        * [`fn withFsType(fsType)`](#fn-speccommandsvolumescinderwithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-speccommandsvolumescinderwithreadonly)
        * [`fn withVolumeID(volumeID)`](#fn-speccommandsvolumescinderwithvolumeid)
        * [`obj spec.commands.volumes.cinder.secretRef`](#obj-speccommandsvolumescindersecretref)
          * [`fn withName(name)`](#fn-speccommandsvolumescindersecretrefwithname)
      * [`obj spec.commands.volumes.configMap`](#obj-speccommandsvolumesconfigmap)
        * [`fn withDefaultMode(defaultMode)`](#fn-speccommandsvolumesconfigmapwithdefaultmode)
        * [`fn withItems(items)`](#fn-speccommandsvolumesconfigmapwithitems)
        * [`fn withItemsMixin(items)`](#fn-speccommandsvolumesconfigmapwithitemsmixin)
        * [`fn withName(name)`](#fn-speccommandsvolumesconfigmapwithname)
        * [`fn withOptional(optional)`](#fn-speccommandsvolumesconfigmapwithoptional)
        * [`obj spec.commands.volumes.configMap.items`](#obj-speccommandsvolumesconfigmapitems)
          * [`fn withKey(key)`](#fn-speccommandsvolumesconfigmapitemswithkey)
          * [`fn withMode(mode)`](#fn-speccommandsvolumesconfigmapitemswithmode)
          * [`fn withPath(path)`](#fn-speccommandsvolumesconfigmapitemswithpath)
      * [`obj spec.commands.volumes.csi`](#obj-speccommandsvolumescsi)
        * [`fn withDriver(driver)`](#fn-speccommandsvolumescsiwithdriver)
        * [`fn withFsType(fsType)`](#fn-speccommandsvolumescsiwithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-speccommandsvolumescsiwithreadonly)
        * [`fn withVolumeAttributes(volumeAttributes)`](#fn-speccommandsvolumescsiwithvolumeattributes)
        * [`fn withVolumeAttributesMixin(volumeAttributes)`](#fn-speccommandsvolumescsiwithvolumeattributesmixin)
        * [`obj spec.commands.volumes.csi.nodePublishSecretRef`](#obj-speccommandsvolumescsinodepublishsecretref)
          * [`fn withName(name)`](#fn-speccommandsvolumescsinodepublishsecretrefwithname)
      * [`obj spec.commands.volumes.downwardAPI`](#obj-speccommandsvolumesdownwardapi)
        * [`fn withDefaultMode(defaultMode)`](#fn-speccommandsvolumesdownwardapiwithdefaultmode)
        * [`fn withItems(items)`](#fn-speccommandsvolumesdownwardapiwithitems)
        * [`fn withItemsMixin(items)`](#fn-speccommandsvolumesdownwardapiwithitemsmixin)
        * [`obj spec.commands.volumes.downwardAPI.items`](#obj-speccommandsvolumesdownwardapiitems)
          * [`fn withMode(mode)`](#fn-speccommandsvolumesdownwardapiitemswithmode)
          * [`fn withPath(path)`](#fn-speccommandsvolumesdownwardapiitemswithpath)
          * [`obj spec.commands.volumes.downwardAPI.items.fieldRef`](#obj-speccommandsvolumesdownwardapiitemsfieldref)
            * [`fn withApiVersion(apiVersion)`](#fn-speccommandsvolumesdownwardapiitemsfieldrefwithapiversion)
            * [`fn withFieldPath(fieldPath)`](#fn-speccommandsvolumesdownwardapiitemsfieldrefwithfieldpath)
          * [`obj spec.commands.volumes.downwardAPI.items.resourceFieldRef`](#obj-speccommandsvolumesdownwardapiitemsresourcefieldref)
            * [`fn withContainerName(containerName)`](#fn-speccommandsvolumesdownwardapiitemsresourcefieldrefwithcontainername)
            * [`fn withDivisor(divisor)`](#fn-speccommandsvolumesdownwardapiitemsresourcefieldrefwithdivisor)
            * [`fn withResource(resource)`](#fn-speccommandsvolumesdownwardapiitemsresourcefieldrefwithresource)
      * [`obj spec.commands.volumes.emptyDir`](#obj-speccommandsvolumesemptydir)
        * [`fn withMedium(medium)`](#fn-speccommandsvolumesemptydirwithmedium)
        * [`fn withSizeLimit(sizeLimit)`](#fn-speccommandsvolumesemptydirwithsizelimit)
      * [`obj spec.commands.volumes.ephemeral`](#obj-speccommandsvolumesephemeral)
        * [`obj spec.commands.volumes.ephemeral.volumeClaimTemplate`](#obj-speccommandsvolumesephemeralvolumeclaimtemplate)
          * [`obj spec.commands.volumes.ephemeral.volumeClaimTemplate.metadata`](#obj-speccommandsvolumesephemeralvolumeclaimtemplatemetadata)
            * [`fn withAnnotations(annotations)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatemetadatawithannotations)
            * [`fn withAnnotationsMixin(annotations)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatemetadatawithannotationsmixin)
            * [`fn withFinalizers(finalizers)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatemetadatawithfinalizers)
            * [`fn withFinalizersMixin(finalizers)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatemetadatawithfinalizersmixin)
            * [`fn withLabels(labels)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatemetadatawithlabels)
            * [`fn withLabelsMixin(labels)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatemetadatawithlabelsmixin)
            * [`fn withName(name)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatemetadatawithname)
            * [`fn withNamespace(namespace)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatemetadatawithnamespace)
          * [`obj spec.commands.volumes.ephemeral.volumeClaimTemplate.spec`](#obj-speccommandsvolumesephemeralvolumeclaimtemplatespec)
            * [`fn withAccessModes(accessModes)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecwithaccessmodes)
            * [`fn withAccessModesMixin(accessModes)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecwithaccessmodesmixin)
            * [`fn withStorageClassName(storageClassName)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecwithstorageclassname)
            * [`fn withVolumeAttributesClassName(volumeAttributesClassName)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecwithvolumeattributesclassname)
            * [`fn withVolumeMode(volumeMode)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecwithvolumemode)
            * [`fn withVolumeName(volumeName)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecwithvolumename)
            * [`obj spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.dataSource`](#obj-speccommandsvolumesephemeralvolumeclaimtemplatespecdatasource)
              * [`fn withApiGroup(apiGroup)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecdatasourcewithapigroup)
              * [`fn withKind(kind)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecdatasourcewithkind)
              * [`fn withName(name)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecdatasourcewithname)
            * [`obj spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef`](#obj-speccommandsvolumesephemeralvolumeclaimtemplatespecdatasourceref)
              * [`fn withApiGroup(apiGroup)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithapigroup)
              * [`fn withKind(kind)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithkind)
              * [`fn withName(name)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithname)
              * [`fn withNamespace(namespace)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithnamespace)
            * [`obj spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.resources`](#obj-speccommandsvolumesephemeralvolumeclaimtemplatespecresources)
              * [`fn withLimits(limits)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecresourceswithlimits)
              * [`fn withLimitsMixin(limits)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecresourceswithlimitsmixin)
              * [`fn withRequests(requests)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecresourceswithrequests)
              * [`fn withRequestsMixin(requests)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecresourceswithrequestsmixin)
            * [`obj spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.selector`](#obj-speccommandsvolumesephemeralvolumeclaimtemplatespecselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabelsmixin)
              * [`obj spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions`](#obj-speccommandsvolumesephemeralvolumeclaimtemplatespecselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccommandsvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvaluesmixin)
      * [`obj spec.commands.volumes.fc`](#obj-speccommandsvolumesfc)
        * [`fn withFsType(fsType)`](#fn-speccommandsvolumesfcwithfstype)
        * [`fn withLun(lun)`](#fn-speccommandsvolumesfcwithlun)
        * [`fn withReadOnly(readOnly)`](#fn-speccommandsvolumesfcwithreadonly)
        * [`fn withTargetWWNs(targetWWNs)`](#fn-speccommandsvolumesfcwithtargetwwns)
        * [`fn withTargetWWNsMixin(targetWWNs)`](#fn-speccommandsvolumesfcwithtargetwwnsmixin)
        * [`fn withWwids(wwids)`](#fn-speccommandsvolumesfcwithwwids)
        * [`fn withWwidsMixin(wwids)`](#fn-speccommandsvolumesfcwithwwidsmixin)
      * [`obj spec.commands.volumes.flexVolume`](#obj-speccommandsvolumesflexvolume)
        * [`fn withDriver(driver)`](#fn-speccommandsvolumesflexvolumewithdriver)
        * [`fn withFsType(fsType)`](#fn-speccommandsvolumesflexvolumewithfstype)
        * [`fn withOptions(options)`](#fn-speccommandsvolumesflexvolumewithoptions)
        * [`fn withOptionsMixin(options)`](#fn-speccommandsvolumesflexvolumewithoptionsmixin)
        * [`fn withReadOnly(readOnly)`](#fn-speccommandsvolumesflexvolumewithreadonly)
        * [`obj spec.commands.volumes.flexVolume.secretRef`](#obj-speccommandsvolumesflexvolumesecretref)
          * [`fn withName(name)`](#fn-speccommandsvolumesflexvolumesecretrefwithname)
      * [`obj spec.commands.volumes.flocker`](#obj-speccommandsvolumesflocker)
        * [`fn withDatasetName(datasetName)`](#fn-speccommandsvolumesflockerwithdatasetname)
        * [`fn withDatasetUUID(datasetUUID)`](#fn-speccommandsvolumesflockerwithdatasetuuid)
      * [`obj spec.commands.volumes.gcePersistentDisk`](#obj-speccommandsvolumesgcepersistentdisk)
        * [`fn withFsType(fsType)`](#fn-speccommandsvolumesgcepersistentdiskwithfstype)
        * [`fn withPartition(partition)`](#fn-speccommandsvolumesgcepersistentdiskwithpartition)
        * [`fn withPdName(pdName)`](#fn-speccommandsvolumesgcepersistentdiskwithpdname)
        * [`fn withReadOnly(readOnly)`](#fn-speccommandsvolumesgcepersistentdiskwithreadonly)
      * [`obj spec.commands.volumes.gitRepo`](#obj-speccommandsvolumesgitrepo)
        * [`fn withDirectory(directory)`](#fn-speccommandsvolumesgitrepowithdirectory)
        * [`fn withRepository(repository)`](#fn-speccommandsvolumesgitrepowithrepository)
        * [`fn withRevision(revision)`](#fn-speccommandsvolumesgitrepowithrevision)
      * [`obj spec.commands.volumes.glusterfs`](#obj-speccommandsvolumesglusterfs)
        * [`fn withEndpoints(endpoints)`](#fn-speccommandsvolumesglusterfswithendpoints)
        * [`fn withPath(path)`](#fn-speccommandsvolumesglusterfswithpath)
        * [`fn withReadOnly(readOnly)`](#fn-speccommandsvolumesglusterfswithreadonly)
      * [`obj spec.commands.volumes.hostPath`](#obj-speccommandsvolumeshostpath)
        * [`fn withPath(path)`](#fn-speccommandsvolumeshostpathwithpath)
        * [`fn withType(type)`](#fn-speccommandsvolumeshostpathwithtype)
      * [`obj spec.commands.volumes.iscsi`](#obj-speccommandsvolumesiscsi)
        * [`fn withChapAuthDiscovery(chapAuthDiscovery)`](#fn-speccommandsvolumesiscsiwithchapauthdiscovery)
        * [`fn withChapAuthSession(chapAuthSession)`](#fn-speccommandsvolumesiscsiwithchapauthsession)
        * [`fn withFsType(fsType)`](#fn-speccommandsvolumesiscsiwithfstype)
        * [`fn withInitiatorName(initiatorName)`](#fn-speccommandsvolumesiscsiwithinitiatorname)
        * [`fn withIqn(iqn)`](#fn-speccommandsvolumesiscsiwithiqn)
        * [`fn withIscsiInterface(iscsiInterface)`](#fn-speccommandsvolumesiscsiwithiscsiinterface)
        * [`fn withLun(lun)`](#fn-speccommandsvolumesiscsiwithlun)
        * [`fn withPortals(portals)`](#fn-speccommandsvolumesiscsiwithportals)
        * [`fn withPortalsMixin(portals)`](#fn-speccommandsvolumesiscsiwithportalsmixin)
        * [`fn withReadOnly(readOnly)`](#fn-speccommandsvolumesiscsiwithreadonly)
        * [`fn withTargetPortal(targetPortal)`](#fn-speccommandsvolumesiscsiwithtargetportal)
        * [`obj spec.commands.volumes.iscsi.secretRef`](#obj-speccommandsvolumesiscsisecretref)
          * [`fn withName(name)`](#fn-speccommandsvolumesiscsisecretrefwithname)
      * [`obj spec.commands.volumes.nfs`](#obj-speccommandsvolumesnfs)
        * [`fn withPath(path)`](#fn-speccommandsvolumesnfswithpath)
        * [`fn withReadOnly(readOnly)`](#fn-speccommandsvolumesnfswithreadonly)
        * [`fn withServer(server)`](#fn-speccommandsvolumesnfswithserver)
      * [`obj spec.commands.volumes.persistentVolumeClaim`](#obj-speccommandsvolumespersistentvolumeclaim)
        * [`fn withClaimName(claimName)`](#fn-speccommandsvolumespersistentvolumeclaimwithclaimname)
        * [`fn withReadOnly(readOnly)`](#fn-speccommandsvolumespersistentvolumeclaimwithreadonly)
      * [`obj spec.commands.volumes.photonPersistentDisk`](#obj-speccommandsvolumesphotonpersistentdisk)
        * [`fn withFsType(fsType)`](#fn-speccommandsvolumesphotonpersistentdiskwithfstype)
        * [`fn withPdID(pdID)`](#fn-speccommandsvolumesphotonpersistentdiskwithpdid)
      * [`obj spec.commands.volumes.portworxVolume`](#obj-speccommandsvolumesportworxvolume)
        * [`fn withFsType(fsType)`](#fn-speccommandsvolumesportworxvolumewithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-speccommandsvolumesportworxvolumewithreadonly)
        * [`fn withVolumeID(volumeID)`](#fn-speccommandsvolumesportworxvolumewithvolumeid)
      * [`obj spec.commands.volumes.projected`](#obj-speccommandsvolumesprojected)
        * [`fn withDefaultMode(defaultMode)`](#fn-speccommandsvolumesprojectedwithdefaultmode)
        * [`fn withSources(sources)`](#fn-speccommandsvolumesprojectedwithsources)
        * [`fn withSourcesMixin(sources)`](#fn-speccommandsvolumesprojectedwithsourcesmixin)
        * [`obj spec.commands.volumes.projected.sources`](#obj-speccommandsvolumesprojectedsources)
          * [`obj spec.commands.volumes.projected.sources.clusterTrustBundle`](#obj-speccommandsvolumesprojectedsourcesclustertrustbundle)
            * [`fn withName(name)`](#fn-speccommandsvolumesprojectedsourcesclustertrustbundlewithname)
            * [`fn withOptional(optional)`](#fn-speccommandsvolumesprojectedsourcesclustertrustbundlewithoptional)
            * [`fn withPath(path)`](#fn-speccommandsvolumesprojectedsourcesclustertrustbundlewithpath)
            * [`fn withSignerName(signerName)`](#fn-speccommandsvolumesprojectedsourcesclustertrustbundlewithsignername)
            * [`obj spec.commands.volumes.projected.sources.clusterTrustBundle.labelSelector`](#obj-speccommandsvolumesprojectedsourcesclustertrustbundlelabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speccommandsvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speccommandsvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speccommandsvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speccommandsvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabelsmixin)
              * [`obj spec.commands.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions`](#obj-speccommandsvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speccommandsvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speccommandsvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speccommandsvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speccommandsvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.commands.volumes.projected.sources.configMap`](#obj-speccommandsvolumesprojectedsourcesconfigmap)
            * [`fn withItems(items)`](#fn-speccommandsvolumesprojectedsourcesconfigmapwithitems)
            * [`fn withItemsMixin(items)`](#fn-speccommandsvolumesprojectedsourcesconfigmapwithitemsmixin)
            * [`fn withName(name)`](#fn-speccommandsvolumesprojectedsourcesconfigmapwithname)
            * [`fn withOptional(optional)`](#fn-speccommandsvolumesprojectedsourcesconfigmapwithoptional)
            * [`obj spec.commands.volumes.projected.sources.configMap.items`](#obj-speccommandsvolumesprojectedsourcesconfigmapitems)
              * [`fn withKey(key)`](#fn-speccommandsvolumesprojectedsourcesconfigmapitemswithkey)
              * [`fn withMode(mode)`](#fn-speccommandsvolumesprojectedsourcesconfigmapitemswithmode)
              * [`fn withPath(path)`](#fn-speccommandsvolumesprojectedsourcesconfigmapitemswithpath)
          * [`obj spec.commands.volumes.projected.sources.downwardAPI`](#obj-speccommandsvolumesprojectedsourcesdownwardapi)
            * [`fn withItems(items)`](#fn-speccommandsvolumesprojectedsourcesdownwardapiwithitems)
            * [`fn withItemsMixin(items)`](#fn-speccommandsvolumesprojectedsourcesdownwardapiwithitemsmixin)
            * [`obj spec.commands.volumes.projected.sources.downwardAPI.items`](#obj-speccommandsvolumesprojectedsourcesdownwardapiitems)
              * [`fn withMode(mode)`](#fn-speccommandsvolumesprojectedsourcesdownwardapiitemswithmode)
              * [`fn withPath(path)`](#fn-speccommandsvolumesprojectedsourcesdownwardapiitemswithpath)
              * [`obj spec.commands.volumes.projected.sources.downwardAPI.items.fieldRef`](#obj-speccommandsvolumesprojectedsourcesdownwardapiitemsfieldref)
                * [`fn withApiVersion(apiVersion)`](#fn-speccommandsvolumesprojectedsourcesdownwardapiitemsfieldrefwithapiversion)
                * [`fn withFieldPath(fieldPath)`](#fn-speccommandsvolumesprojectedsourcesdownwardapiitemsfieldrefwithfieldpath)
              * [`obj spec.commands.volumes.projected.sources.downwardAPI.items.resourceFieldRef`](#obj-speccommandsvolumesprojectedsourcesdownwardapiitemsresourcefieldref)
                * [`fn withContainerName(containerName)`](#fn-speccommandsvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithcontainername)
                * [`fn withDivisor(divisor)`](#fn-speccommandsvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithdivisor)
                * [`fn withResource(resource)`](#fn-speccommandsvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithresource)
          * [`obj spec.commands.volumes.projected.sources.secret`](#obj-speccommandsvolumesprojectedsourcessecret)
            * [`fn withItems(items)`](#fn-speccommandsvolumesprojectedsourcessecretwithitems)
            * [`fn withItemsMixin(items)`](#fn-speccommandsvolumesprojectedsourcessecretwithitemsmixin)
            * [`fn withName(name)`](#fn-speccommandsvolumesprojectedsourcessecretwithname)
            * [`fn withOptional(optional)`](#fn-speccommandsvolumesprojectedsourcessecretwithoptional)
            * [`obj spec.commands.volumes.projected.sources.secret.items`](#obj-speccommandsvolumesprojectedsourcessecretitems)
              * [`fn withKey(key)`](#fn-speccommandsvolumesprojectedsourcessecretitemswithkey)
              * [`fn withMode(mode)`](#fn-speccommandsvolumesprojectedsourcessecretitemswithmode)
              * [`fn withPath(path)`](#fn-speccommandsvolumesprojectedsourcessecretitemswithpath)
          * [`obj spec.commands.volumes.projected.sources.serviceAccountToken`](#obj-speccommandsvolumesprojectedsourcesserviceaccounttoken)
            * [`fn withAudience(audience)`](#fn-speccommandsvolumesprojectedsourcesserviceaccounttokenwithaudience)
            * [`fn withExpirationSeconds(expirationSeconds)`](#fn-speccommandsvolumesprojectedsourcesserviceaccounttokenwithexpirationseconds)
            * [`fn withPath(path)`](#fn-speccommandsvolumesprojectedsourcesserviceaccounttokenwithpath)
      * [`obj spec.commands.volumes.quobyte`](#obj-speccommandsvolumesquobyte)
        * [`fn withGroup(group)`](#fn-speccommandsvolumesquobytewithgroup)
        * [`fn withReadOnly(readOnly)`](#fn-speccommandsvolumesquobytewithreadonly)
        * [`fn withRegistry(registry)`](#fn-speccommandsvolumesquobytewithregistry)
        * [`fn withTenant(tenant)`](#fn-speccommandsvolumesquobytewithtenant)
        * [`fn withUser(user)`](#fn-speccommandsvolumesquobytewithuser)
        * [`fn withVolume(volume)`](#fn-speccommandsvolumesquobytewithvolume)
      * [`obj spec.commands.volumes.rbd`](#obj-speccommandsvolumesrbd)
        * [`fn withFsType(fsType)`](#fn-speccommandsvolumesrbdwithfstype)
        * [`fn withImage(image)`](#fn-speccommandsvolumesrbdwithimage)
        * [`fn withKeyring(keyring)`](#fn-speccommandsvolumesrbdwithkeyring)
        * [`fn withMonitors(monitors)`](#fn-speccommandsvolumesrbdwithmonitors)
        * [`fn withMonitorsMixin(monitors)`](#fn-speccommandsvolumesrbdwithmonitorsmixin)
        * [`fn withPool(pool)`](#fn-speccommandsvolumesrbdwithpool)
        * [`fn withReadOnly(readOnly)`](#fn-speccommandsvolumesrbdwithreadonly)
        * [`fn withUser(user)`](#fn-speccommandsvolumesrbdwithuser)
        * [`obj spec.commands.volumes.rbd.secretRef`](#obj-speccommandsvolumesrbdsecretref)
          * [`fn withName(name)`](#fn-speccommandsvolumesrbdsecretrefwithname)
      * [`obj spec.commands.volumes.scaleIO`](#obj-speccommandsvolumesscaleio)
        * [`fn withFsType(fsType)`](#fn-speccommandsvolumesscaleiowithfstype)
        * [`fn withGateway(gateway)`](#fn-speccommandsvolumesscaleiowithgateway)
        * [`fn withProtectionDomain(protectionDomain)`](#fn-speccommandsvolumesscaleiowithprotectiondomain)
        * [`fn withReadOnly(readOnly)`](#fn-speccommandsvolumesscaleiowithreadonly)
        * [`fn withSslEnabled(sslEnabled)`](#fn-speccommandsvolumesscaleiowithsslenabled)
        * [`fn withStorageMode(storageMode)`](#fn-speccommandsvolumesscaleiowithstoragemode)
        * [`fn withStoragePool(storagePool)`](#fn-speccommandsvolumesscaleiowithstoragepool)
        * [`fn withSystem(system)`](#fn-speccommandsvolumesscaleiowithsystem)
        * [`fn withVolumeName(volumeName)`](#fn-speccommandsvolumesscaleiowithvolumename)
        * [`obj spec.commands.volumes.scaleIO.secretRef`](#obj-speccommandsvolumesscaleiosecretref)
          * [`fn withName(name)`](#fn-speccommandsvolumesscaleiosecretrefwithname)
      * [`obj spec.commands.volumes.secret`](#obj-speccommandsvolumessecret)
        * [`fn withDefaultMode(defaultMode)`](#fn-speccommandsvolumessecretwithdefaultmode)
        * [`fn withItems(items)`](#fn-speccommandsvolumessecretwithitems)
        * [`fn withItemsMixin(items)`](#fn-speccommandsvolumessecretwithitemsmixin)
        * [`fn withOptional(optional)`](#fn-speccommandsvolumessecretwithoptional)
        * [`fn withSecretName(secretName)`](#fn-speccommandsvolumessecretwithsecretname)
        * [`obj spec.commands.volumes.secret.items`](#obj-speccommandsvolumessecretitems)
          * [`fn withKey(key)`](#fn-speccommandsvolumessecretitemswithkey)
          * [`fn withMode(mode)`](#fn-speccommandsvolumessecretitemswithmode)
          * [`fn withPath(path)`](#fn-speccommandsvolumessecretitemswithpath)
      * [`obj spec.commands.volumes.storageos`](#obj-speccommandsvolumesstorageos)
        * [`fn withFsType(fsType)`](#fn-speccommandsvolumesstorageoswithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-speccommandsvolumesstorageoswithreadonly)
        * [`fn withVolumeName(volumeName)`](#fn-speccommandsvolumesstorageoswithvolumename)
        * [`fn withVolumeNamespace(volumeNamespace)`](#fn-speccommandsvolumesstorageoswithvolumenamespace)
        * [`obj spec.commands.volumes.storageos.secretRef`](#obj-speccommandsvolumesstorageossecretref)
          * [`fn withName(name)`](#fn-speccommandsvolumesstorageossecretrefwithname)
      * [`obj spec.commands.volumes.vsphereVolume`](#obj-speccommandsvolumesvspherevolume)
        * [`fn withFsType(fsType)`](#fn-speccommandsvolumesvspherevolumewithfstype)
        * [`fn withStoragePolicyID(storagePolicyID)`](#fn-speccommandsvolumesvspherevolumewithstoragepolicyid)
        * [`fn withStoragePolicyName(storagePolicyName)`](#fn-speccommandsvolumesvspherevolumewithstoragepolicyname)
        * [`fn withVolumePath(volumePath)`](#fn-speccommandsvolumesvspherevolumewithvolumepath)
  * [`obj spec.containerSecurityContext`](#obj-speccontainersecuritycontext)
    * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-speccontainersecuritycontextwithallowprivilegeescalation)
    * [`fn withPrivileged(privileged)`](#fn-speccontainersecuritycontextwithprivileged)
    * [`fn withProcMount(procMount)`](#fn-speccontainersecuritycontextwithprocmount)
    * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-speccontainersecuritycontextwithreadonlyrootfilesystem)
    * [`fn withRunAsGroup(runAsGroup)`](#fn-speccontainersecuritycontextwithrunasgroup)
    * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-speccontainersecuritycontextwithrunasnonroot)
    * [`fn withRunAsUser(runAsUser)`](#fn-speccontainersecuritycontextwithrunasuser)
    * [`obj spec.containerSecurityContext.appArmorProfile`](#obj-speccontainersecuritycontextapparmorprofile)
      * [`fn withLocalhostProfile(localhostProfile)`](#fn-speccontainersecuritycontextapparmorprofilewithlocalhostprofile)
      * [`fn withType(type)`](#fn-speccontainersecuritycontextapparmorprofilewithtype)
    * [`obj spec.containerSecurityContext.capabilities`](#obj-speccontainersecuritycontextcapabilities)
      * [`fn withAdd(add)`](#fn-speccontainersecuritycontextcapabilitieswithadd)
      * [`fn withAddMixin(add)`](#fn-speccontainersecuritycontextcapabilitieswithaddmixin)
      * [`fn withDrop(drop)`](#fn-speccontainersecuritycontextcapabilitieswithdrop)
      * [`fn withDropMixin(drop)`](#fn-speccontainersecuritycontextcapabilitieswithdropmixin)
    * [`obj spec.containerSecurityContext.seLinuxOptions`](#obj-speccontainersecuritycontextselinuxoptions)
      * [`fn withLevel(level)`](#fn-speccontainersecuritycontextselinuxoptionswithlevel)
      * [`fn withRole(role)`](#fn-speccontainersecuritycontextselinuxoptionswithrole)
      * [`fn withType(type)`](#fn-speccontainersecuritycontextselinuxoptionswithtype)
      * [`fn withUser(user)`](#fn-speccontainersecuritycontextselinuxoptionswithuser)
    * [`obj spec.containerSecurityContext.seccompProfile`](#obj-speccontainersecuritycontextseccompprofile)
      * [`fn withLocalhostProfile(localhostProfile)`](#fn-speccontainersecuritycontextseccompprofilewithlocalhostprofile)
      * [`fn withType(type)`](#fn-speccontainersecuritycontextseccompprofilewithtype)
    * [`obj spec.containerSecurityContext.windowsOptions`](#obj-speccontainersecuritycontextwindowsoptions)
      * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-speccontainersecuritycontextwindowsoptionswithgmsacredentialspec)
      * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-speccontainersecuritycontextwindowsoptionswithgmsacredentialspecname)
      * [`fn withHostProcess(hostProcess)`](#fn-speccontainersecuritycontextwindowsoptionswithhostprocess)
      * [`fn withRunAsUserName(runAsUserName)`](#fn-speccontainersecuritycontextwindowsoptionswithrunasusername)
  * [`obj spec.imagePullSecret`](#obj-specimagepullsecret)
    * [`fn withName(name)`](#fn-specimagepullsecretwithname)
  * [`obj spec.securityContext`](#obj-specsecuritycontext)
    * [`fn withFsGroup(fsGroup)`](#fn-specsecuritycontextwithfsgroup)
    * [`fn withFsGroupChangePolicy(fsGroupChangePolicy)`](#fn-specsecuritycontextwithfsgroupchangepolicy)
    * [`fn withRunAsGroup(runAsGroup)`](#fn-specsecuritycontextwithrunasgroup)
    * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specsecuritycontextwithrunasnonroot)
    * [`fn withRunAsUser(runAsUser)`](#fn-specsecuritycontextwithrunasuser)
    * [`fn withSupplementalGroups(supplementalGroups)`](#fn-specsecuritycontextwithsupplementalgroups)
    * [`fn withSupplementalGroupsMixin(supplementalGroups)`](#fn-specsecuritycontextwithsupplementalgroupsmixin)
    * [`fn withSysctls(sysctls)`](#fn-specsecuritycontextwithsysctls)
    * [`fn withSysctlsMixin(sysctls)`](#fn-specsecuritycontextwithsysctlsmixin)
    * [`obj spec.securityContext.appArmorProfile`](#obj-specsecuritycontextapparmorprofile)
      * [`fn withLocalhostProfile(localhostProfile)`](#fn-specsecuritycontextapparmorprofilewithlocalhostprofile)
      * [`fn withType(type)`](#fn-specsecuritycontextapparmorprofilewithtype)
    * [`obj spec.securityContext.seLinuxOptions`](#obj-specsecuritycontextselinuxoptions)
      * [`fn withLevel(level)`](#fn-specsecuritycontextselinuxoptionswithlevel)
      * [`fn withRole(role)`](#fn-specsecuritycontextselinuxoptionswithrole)
      * [`fn withType(type)`](#fn-specsecuritycontextselinuxoptionswithtype)
      * [`fn withUser(user)`](#fn-specsecuritycontextselinuxoptionswithuser)
    * [`obj spec.securityContext.seccompProfile`](#obj-specsecuritycontextseccompprofile)
      * [`fn withLocalhostProfile(localhostProfile)`](#fn-specsecuritycontextseccompprofilewithlocalhostprofile)
      * [`fn withType(type)`](#fn-specsecuritycontextseccompprofilewithtype)
    * [`obj spec.securityContext.sysctls`](#obj-specsecuritycontextsysctls)
      * [`fn withName(name)`](#fn-specsecuritycontextsysctlswithname)
      * [`fn withValue(value)`](#fn-specsecuritycontextsysctlswithvalue)
    * [`obj spec.securityContext.windowsOptions`](#obj-specsecuritycontextwindowsoptions)
      * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specsecuritycontextwindowsoptionswithgmsacredentialspec)
      * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specsecuritycontextwindowsoptionswithgmsacredentialspecname)
      * [`fn withHostProcess(hostProcess)`](#fn-specsecuritycontextwindowsoptionswithhostprocess)
      * [`fn withRunAsUserName(runAsUserName)`](#fn-specsecuritycontextwindowsoptionswithrunasusername)
  * [`obj spec.tenant`](#obj-spectenant)
    * [`fn withName(name)`](#fn-spectenantwithname)
    * [`fn withNamespace(namespace)`](#fn-spectenantwithnamespace)

## Fields

### fn new

```ts
new(name)
```

new returns an instance of MinIOJob

## obj metadata

"ObjectMeta is metadata that all persisted resources must have, which includes all objects users must create."

### fn metadata.withAnnotations

```ts
withAnnotations(annotations)
```

"Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations"

### fn metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```

"Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations"

**Note:** This function appends passed data to existing values

### fn metadata.withClusterName

```ts
withClusterName(clusterName)
```

"The name of the cluster which the object belongs to. This is used to distinguish resources with same name and namespace in different clusters. This field is not set anywhere right now and apiserver is going to ignore it if set in create or update request."

### fn metadata.withCreationTimestamp

```ts
withCreationTimestamp(creationTimestamp)
```

"Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers."

### fn metadata.withDeletionGracePeriodSeconds

```ts
withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)
```

"Number of seconds allowed for this object to gracefully terminate before it will be removed from the system. Only set when deletionTimestamp is also set. May only be shortened. Read-only."

### fn metadata.withDeletionTimestamp

```ts
withDeletionTimestamp(deletionTimestamp)
```

"Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers."

### fn metadata.withFinalizers

```ts
withFinalizers(finalizers)
```

"Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed. Finalizers may be processed and removed in any order.  Order is NOT enforced because it introduces significant risk of stuck finalizers. finalizers is a shared field, any actor with permission can reorder it. If the finalizer list is processed in order, then this can lead to a situation in which the component responsible for the first finalizer in the list is waiting for a signal (field value, external system, or other) produced by a component responsible for a finalizer later in the list, resulting in a deadlock. Without enforced ordering finalizers are free to order amongst themselves and are not vulnerable to ordering changes in the list."

### fn metadata.withFinalizersMixin

```ts
withFinalizersMixin(finalizers)
```

"Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed. Finalizers may be processed and removed in any order.  Order is NOT enforced because it introduces significant risk of stuck finalizers. finalizers is a shared field, any actor with permission can reorder it. If the finalizer list is processed in order, then this can lead to a situation in which the component responsible for the first finalizer in the list is waiting for a signal (field value, external system, or other) produced by a component responsible for a finalizer later in the list, resulting in a deadlock. Without enforced ordering finalizers are free to order amongst themselves and are not vulnerable to ordering changes in the list."

**Note:** This function appends passed data to existing values

### fn metadata.withGenerateName

```ts
withGenerateName(generateName)
```

"GenerateName is an optional prefix, used by the server, to generate a unique name ONLY IF the Name field has not been provided. If this field is used, the name returned to the client will be different than the name passed. This value will also be combined with a unique suffix. The provided value has the same validation rules as the Name field, and may be truncated by the length of the suffix required to make the value unique on the server.\n\nIf this field is specified and the generated name exists, the server will NOT return a 409 - instead, it will either return 201 Created or 500 with Reason ServerTimeout indicating a unique name could not be found in the time allotted, and the client should retry (optionally after the time indicated in the Retry-After header).\n\nApplied only if Name is not specified. More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#idempotency"

### fn metadata.withGeneration

```ts
withGeneration(generation)
```

"A sequence number representing a specific generation of the desired state. Populated by the system. Read-only."

### fn metadata.withLabels

```ts
withLabels(labels)
```

"Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels"

### fn metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```

"Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels"

**Note:** This function appends passed data to existing values

### fn metadata.withName

```ts
withName(name)
```

"Name must be unique within a namespace. Is required when creating resources, although some resources may allow a client to request the generation of an appropriate name automatically. Name is primarily intended for creation idempotence and configuration definition. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/identifiers#names"

### fn metadata.withNamespace

```ts
withNamespace(namespace)
```

"Namespace defines the space within which each name must be unique. An empty namespace is equivalent to the \"default\" namespace, but \"default\" is the canonical representation. Not all objects are required to be scoped to a namespace - the value of this field for those objects will be empty.\n\nMust be a DNS_LABEL. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/namespaces"

### fn metadata.withOwnerReferences

```ts
withOwnerReferences(ownerReferences)
```

"List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller."

### fn metadata.withOwnerReferencesMixin

```ts
withOwnerReferencesMixin(ownerReferences)
```

"List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller."

**Note:** This function appends passed data to existing values

### fn metadata.withResourceVersion

```ts
withResourceVersion(resourceVersion)
```

"An opaque value that represents the internal version of this object that can be used by clients to determine when objects have changed. May be used for optimistic concurrency, change detection, and the watch operation on a resource or set of resources. Clients must treat these values as opaque and passed unmodified back to the server. They may only be valid for a particular resource or set of resources.\n\nPopulated by the system. Read-only. Value must be treated as opaque by clients and . More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#concurrency-control-and-consistency"

### fn metadata.withSelfLink

```ts
withSelfLink(selfLink)
```

"SelfLink is a URL representing this object. Populated by the system. Read-only.\n\nDEPRECATED Kubernetes will stop propagating this field in 1.20 release and the field is planned to be removed in 1.21 release."

### fn metadata.withUid

```ts
withUid(uid)
```

"UID is the unique in time and space value for this object. It is typically generated by the server on successful creation of a resource and is not allowed to change on PUT operations.\n\nPopulated by the system. Read-only. More info: http://kubernetes.io/docs/user-guide/identifiers#uids"

## obj spec



### fn spec.withCommands

```ts
withCommands(commands)
```



### fn spec.withCommandsMixin

```ts
withCommandsMixin(commands)
```



**Note:** This function appends passed data to existing values

### fn spec.withExecution

```ts
withExecution(execution)
```



### fn spec.withFailureStrategy

```ts
withFailureStrategy(failureStrategy)
```



### fn spec.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.withImagePullSecret

```ts
withImagePullSecret(imagePullSecret)
```



### fn spec.withImagePullSecretMixin

```ts
withImagePullSecretMixin(imagePullSecret)
```



**Note:** This function appends passed data to existing values

### fn spec.withMcImage

```ts
withMcImage(mcImage)
```



### fn spec.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



## obj spec.commands



### fn spec.commands.withArgs

```ts
withArgs(args)
```



### fn spec.commands.withArgsMixin

```ts
withArgsMixin(args)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.withCommand

```ts
withCommand(command)
```



### fn spec.commands.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.withDependsOn

```ts
withDependsOn(dependsOn)
```



### fn spec.commands.withDependsOnMixin

```ts
withDependsOnMixin(dependsOn)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.withEnv

```ts
withEnv(env)
```



### fn spec.commands.withEnvFrom

```ts
withEnvFrom(envFrom)
```



### fn spec.commands.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.withName

```ts
withName(name)
```



### fn spec.commands.withOp

```ts
withOp(op)
```



### fn spec.commands.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.commands.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.withVolumes

```ts
withVolumes(volumes)
```



### fn spec.commands.withVolumesMixin

```ts
withVolumesMixin(volumes)
```



**Note:** This function appends passed data to existing values

## obj spec.commands.env



### fn spec.commands.env.withName

```ts
withName(name)
```



### fn spec.commands.env.withValue

```ts
withValue(value)
```



## obj spec.commands.env.valueFrom



## obj spec.commands.env.valueFrom.configMapKeyRef



### fn spec.commands.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.commands.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.commands.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.commands.env.valueFrom.fieldRef



### fn spec.commands.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.commands.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.commands.env.valueFrom.resourceFieldRef



### fn spec.commands.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.commands.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.commands.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.commands.env.valueFrom.secretKeyRef



### fn spec.commands.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.commands.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.commands.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.commands.envFrom



### fn spec.commands.envFrom.withPrefix

```ts
withPrefix(prefix)
```



## obj spec.commands.envFrom.configMapRef



### fn spec.commands.envFrom.configMapRef.withName

```ts
withName(name)
```



### fn spec.commands.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```



## obj spec.commands.envFrom.secretRef



### fn spec.commands.envFrom.secretRef.withName

```ts
withName(name)
```



### fn spec.commands.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```



## obj spec.commands.resources



### fn spec.commands.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.commands.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.commands.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.commands.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.commands.resources.claims



### fn spec.commands.resources.claims.withName

```ts
withName(name)
```



## obj spec.commands.volumeMounts



### fn spec.commands.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.commands.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.commands.volumeMounts.withName

```ts
withName(name)
```



### fn spec.commands.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.commands.volumeMounts.withRecursiveReadOnly

```ts
withRecursiveReadOnly(recursiveReadOnly)
```



### fn spec.commands.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.commands.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.commands.volumes



### fn spec.commands.volumes.withName

```ts
withName(name)
```



## obj spec.commands.volumes.awsElasticBlockStore



### fn spec.commands.volumes.awsElasticBlockStore.withFsType

```ts
withFsType(fsType)
```



### fn spec.commands.volumes.awsElasticBlockStore.withPartition

```ts
withPartition(partition)
```



### fn spec.commands.volumes.awsElasticBlockStore.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.commands.volumes.awsElasticBlockStore.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.commands.volumes.azureDisk



### fn spec.commands.volumes.azureDisk.withCachingMode

```ts
withCachingMode(cachingMode)
```



### fn spec.commands.volumes.azureDisk.withDiskName

```ts
withDiskName(diskName)
```



### fn spec.commands.volumes.azureDisk.withDiskURI

```ts
withDiskURI(diskURI)
```



### fn spec.commands.volumes.azureDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.commands.volumes.azureDisk.withKind

```ts
withKind(kind)
```



### fn spec.commands.volumes.azureDisk.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.commands.volumes.azureFile



### fn spec.commands.volumes.azureFile.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.commands.volumes.azureFile.withSecretName

```ts
withSecretName(secretName)
```



### fn spec.commands.volumes.azureFile.withShareName

```ts
withShareName(shareName)
```



## obj spec.commands.volumes.cephfs



### fn spec.commands.volumes.cephfs.withMonitors

```ts
withMonitors(monitors)
```



### fn spec.commands.volumes.cephfs.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.volumes.cephfs.withPath

```ts
withPath(path)
```



### fn spec.commands.volumes.cephfs.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.commands.volumes.cephfs.withSecretFile

```ts
withSecretFile(secretFile)
```



### fn spec.commands.volumes.cephfs.withUser

```ts
withUser(user)
```



## obj spec.commands.volumes.cephfs.secretRef



### fn spec.commands.volumes.cephfs.secretRef.withName

```ts
withName(name)
```



## obj spec.commands.volumes.cinder



### fn spec.commands.volumes.cinder.withFsType

```ts
withFsType(fsType)
```



### fn spec.commands.volumes.cinder.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.commands.volumes.cinder.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.commands.volumes.cinder.secretRef



### fn spec.commands.volumes.cinder.secretRef.withName

```ts
withName(name)
```



## obj spec.commands.volumes.configMap



### fn spec.commands.volumes.configMap.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.commands.volumes.configMap.withItems

```ts
withItems(items)
```



### fn spec.commands.volumes.configMap.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.volumes.configMap.withName

```ts
withName(name)
```



### fn spec.commands.volumes.configMap.withOptional

```ts
withOptional(optional)
```



## obj spec.commands.volumes.configMap.items



### fn spec.commands.volumes.configMap.items.withKey

```ts
withKey(key)
```



### fn spec.commands.volumes.configMap.items.withMode

```ts
withMode(mode)
```



### fn spec.commands.volumes.configMap.items.withPath

```ts
withPath(path)
```



## obj spec.commands.volumes.csi



### fn spec.commands.volumes.csi.withDriver

```ts
withDriver(driver)
```



### fn spec.commands.volumes.csi.withFsType

```ts
withFsType(fsType)
```



### fn spec.commands.volumes.csi.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.commands.volumes.csi.withVolumeAttributes

```ts
withVolumeAttributes(volumeAttributes)
```



### fn spec.commands.volumes.csi.withVolumeAttributesMixin

```ts
withVolumeAttributesMixin(volumeAttributes)
```



**Note:** This function appends passed data to existing values

## obj spec.commands.volumes.csi.nodePublishSecretRef



### fn spec.commands.volumes.csi.nodePublishSecretRef.withName

```ts
withName(name)
```



## obj spec.commands.volumes.downwardAPI



### fn spec.commands.volumes.downwardAPI.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.commands.volumes.downwardAPI.withItems

```ts
withItems(items)
```



### fn spec.commands.volumes.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

## obj spec.commands.volumes.downwardAPI.items



### fn spec.commands.volumes.downwardAPI.items.withMode

```ts
withMode(mode)
```



### fn spec.commands.volumes.downwardAPI.items.withPath

```ts
withPath(path)
```



## obj spec.commands.volumes.downwardAPI.items.fieldRef



### fn spec.commands.volumes.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.commands.volumes.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.commands.volumes.downwardAPI.items.resourceFieldRef



### fn spec.commands.volumes.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.commands.volumes.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.commands.volumes.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.commands.volumes.emptyDir



### fn spec.commands.volumes.emptyDir.withMedium

```ts
withMedium(medium)
```



### fn spec.commands.volumes.emptyDir.withSizeLimit

```ts
withSizeLimit(sizeLimit)
```



## obj spec.commands.volumes.ephemeral



## obj spec.commands.volumes.ephemeral.volumeClaimTemplate



## obj spec.commands.volumes.ephemeral.volumeClaimTemplate.metadata



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.metadata.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.metadata.withFinalizers

```ts
withFinalizers(finalizers)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.metadata.withFinalizersMixin

```ts
withFinalizersMixin(finalizers)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.metadata.withLabels

```ts
withLabels(labels)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.metadata.withName

```ts
withName(name)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.metadata.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.commands.volumes.ephemeral.volumeClaimTemplate.spec



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.withAccessModes

```ts
withAccessModes(accessModes)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.withAccessModesMixin

```ts
withAccessModesMixin(accessModes)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.withStorageClassName

```ts
withStorageClassName(storageClassName)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeAttributesClassName

```ts
withVolumeAttributesClassName(volumeAttributesClassName)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeMode

```ts
withVolumeMode(volumeMode)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.dataSource



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withKind

```ts
withKind(kind)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withName

```ts
withName(name)
```



## obj spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withKind

```ts
withKind(kind)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withName

```ts
withName(name)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.resources



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.selector



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.commands.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.commands.volumes.fc



### fn spec.commands.volumes.fc.withFsType

```ts
withFsType(fsType)
```



### fn spec.commands.volumes.fc.withLun

```ts
withLun(lun)
```



### fn spec.commands.volumes.fc.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.commands.volumes.fc.withTargetWWNs

```ts
withTargetWWNs(targetWWNs)
```



### fn spec.commands.volumes.fc.withTargetWWNsMixin

```ts
withTargetWWNsMixin(targetWWNs)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.volumes.fc.withWwids

```ts
withWwids(wwids)
```



### fn spec.commands.volumes.fc.withWwidsMixin

```ts
withWwidsMixin(wwids)
```



**Note:** This function appends passed data to existing values

## obj spec.commands.volumes.flexVolume



### fn spec.commands.volumes.flexVolume.withDriver

```ts
withDriver(driver)
```



### fn spec.commands.volumes.flexVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.commands.volumes.flexVolume.withOptions

```ts
withOptions(options)
```



### fn spec.commands.volumes.flexVolume.withOptionsMixin

```ts
withOptionsMixin(options)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.volumes.flexVolume.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.commands.volumes.flexVolume.secretRef



### fn spec.commands.volumes.flexVolume.secretRef.withName

```ts
withName(name)
```



## obj spec.commands.volumes.flocker



### fn spec.commands.volumes.flocker.withDatasetName

```ts
withDatasetName(datasetName)
```



### fn spec.commands.volumes.flocker.withDatasetUUID

```ts
withDatasetUUID(datasetUUID)
```



## obj spec.commands.volumes.gcePersistentDisk



### fn spec.commands.volumes.gcePersistentDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.commands.volumes.gcePersistentDisk.withPartition

```ts
withPartition(partition)
```



### fn spec.commands.volumes.gcePersistentDisk.withPdName

```ts
withPdName(pdName)
```



### fn spec.commands.volumes.gcePersistentDisk.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.commands.volumes.gitRepo



### fn spec.commands.volumes.gitRepo.withDirectory

```ts
withDirectory(directory)
```



### fn spec.commands.volumes.gitRepo.withRepository

```ts
withRepository(repository)
```



### fn spec.commands.volumes.gitRepo.withRevision

```ts
withRevision(revision)
```



## obj spec.commands.volumes.glusterfs



### fn spec.commands.volumes.glusterfs.withEndpoints

```ts
withEndpoints(endpoints)
```



### fn spec.commands.volumes.glusterfs.withPath

```ts
withPath(path)
```



### fn spec.commands.volumes.glusterfs.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.commands.volumes.hostPath



### fn spec.commands.volumes.hostPath.withPath

```ts
withPath(path)
```



### fn spec.commands.volumes.hostPath.withType

```ts
withType(type)
```



## obj spec.commands.volumes.iscsi



### fn spec.commands.volumes.iscsi.withChapAuthDiscovery

```ts
withChapAuthDiscovery(chapAuthDiscovery)
```



### fn spec.commands.volumes.iscsi.withChapAuthSession

```ts
withChapAuthSession(chapAuthSession)
```



### fn spec.commands.volumes.iscsi.withFsType

```ts
withFsType(fsType)
```



### fn spec.commands.volumes.iscsi.withInitiatorName

```ts
withInitiatorName(initiatorName)
```



### fn spec.commands.volumes.iscsi.withIqn

```ts
withIqn(iqn)
```



### fn spec.commands.volumes.iscsi.withIscsiInterface

```ts
withIscsiInterface(iscsiInterface)
```



### fn spec.commands.volumes.iscsi.withLun

```ts
withLun(lun)
```



### fn spec.commands.volumes.iscsi.withPortals

```ts
withPortals(portals)
```



### fn spec.commands.volumes.iscsi.withPortalsMixin

```ts
withPortalsMixin(portals)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.volumes.iscsi.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.commands.volumes.iscsi.withTargetPortal

```ts
withTargetPortal(targetPortal)
```



## obj spec.commands.volumes.iscsi.secretRef



### fn spec.commands.volumes.iscsi.secretRef.withName

```ts
withName(name)
```



## obj spec.commands.volumes.nfs



### fn spec.commands.volumes.nfs.withPath

```ts
withPath(path)
```



### fn spec.commands.volumes.nfs.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.commands.volumes.nfs.withServer

```ts
withServer(server)
```



## obj spec.commands.volumes.persistentVolumeClaim



### fn spec.commands.volumes.persistentVolumeClaim.withClaimName

```ts
withClaimName(claimName)
```



### fn spec.commands.volumes.persistentVolumeClaim.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.commands.volumes.photonPersistentDisk



### fn spec.commands.volumes.photonPersistentDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.commands.volumes.photonPersistentDisk.withPdID

```ts
withPdID(pdID)
```



## obj spec.commands.volumes.portworxVolume



### fn spec.commands.volumes.portworxVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.commands.volumes.portworxVolume.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.commands.volumes.portworxVolume.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.commands.volumes.projected



### fn spec.commands.volumes.projected.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.commands.volumes.projected.withSources

```ts
withSources(sources)
```



### fn spec.commands.volumes.projected.withSourcesMixin

```ts
withSourcesMixin(sources)
```



**Note:** This function appends passed data to existing values

## obj spec.commands.volumes.projected.sources



## obj spec.commands.volumes.projected.sources.clusterTrustBundle



### fn spec.commands.volumes.projected.sources.clusterTrustBundle.withName

```ts
withName(name)
```



### fn spec.commands.volumes.projected.sources.clusterTrustBundle.withOptional

```ts
withOptional(optional)
```



### fn spec.commands.volumes.projected.sources.clusterTrustBundle.withPath

```ts
withPath(path)
```



### fn spec.commands.volumes.projected.sources.clusterTrustBundle.withSignerName

```ts
withSignerName(signerName)
```



## obj spec.commands.volumes.projected.sources.clusterTrustBundle.labelSelector



### fn spec.commands.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.commands.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.commands.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.commands.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions



### fn spec.commands.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.commands.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.commands.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.commands.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.commands.volumes.projected.sources.configMap



### fn spec.commands.volumes.projected.sources.configMap.withItems

```ts
withItems(items)
```



### fn spec.commands.volumes.projected.sources.configMap.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.volumes.projected.sources.configMap.withName

```ts
withName(name)
```



### fn spec.commands.volumes.projected.sources.configMap.withOptional

```ts
withOptional(optional)
```



## obj spec.commands.volumes.projected.sources.configMap.items



### fn spec.commands.volumes.projected.sources.configMap.items.withKey

```ts
withKey(key)
```



### fn spec.commands.volumes.projected.sources.configMap.items.withMode

```ts
withMode(mode)
```



### fn spec.commands.volumes.projected.sources.configMap.items.withPath

```ts
withPath(path)
```



## obj spec.commands.volumes.projected.sources.downwardAPI



### fn spec.commands.volumes.projected.sources.downwardAPI.withItems

```ts
withItems(items)
```



### fn spec.commands.volumes.projected.sources.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

## obj spec.commands.volumes.projected.sources.downwardAPI.items



### fn spec.commands.volumes.projected.sources.downwardAPI.items.withMode

```ts
withMode(mode)
```



### fn spec.commands.volumes.projected.sources.downwardAPI.items.withPath

```ts
withPath(path)
```



## obj spec.commands.volumes.projected.sources.downwardAPI.items.fieldRef



### fn spec.commands.volumes.projected.sources.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.commands.volumes.projected.sources.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.commands.volumes.projected.sources.downwardAPI.items.resourceFieldRef



### fn spec.commands.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.commands.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.commands.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.commands.volumes.projected.sources.secret



### fn spec.commands.volumes.projected.sources.secret.withItems

```ts
withItems(items)
```



### fn spec.commands.volumes.projected.sources.secret.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.volumes.projected.sources.secret.withName

```ts
withName(name)
```



### fn spec.commands.volumes.projected.sources.secret.withOptional

```ts
withOptional(optional)
```



## obj spec.commands.volumes.projected.sources.secret.items



### fn spec.commands.volumes.projected.sources.secret.items.withKey

```ts
withKey(key)
```



### fn spec.commands.volumes.projected.sources.secret.items.withMode

```ts
withMode(mode)
```



### fn spec.commands.volumes.projected.sources.secret.items.withPath

```ts
withPath(path)
```



## obj spec.commands.volumes.projected.sources.serviceAccountToken



### fn spec.commands.volumes.projected.sources.serviceAccountToken.withAudience

```ts
withAudience(audience)
```



### fn spec.commands.volumes.projected.sources.serviceAccountToken.withExpirationSeconds

```ts
withExpirationSeconds(expirationSeconds)
```



### fn spec.commands.volumes.projected.sources.serviceAccountToken.withPath

```ts
withPath(path)
```



## obj spec.commands.volumes.quobyte



### fn spec.commands.volumes.quobyte.withGroup

```ts
withGroup(group)
```



### fn spec.commands.volumes.quobyte.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.commands.volumes.quobyte.withRegistry

```ts
withRegistry(registry)
```



### fn spec.commands.volumes.quobyte.withTenant

```ts
withTenant(tenant)
```



### fn spec.commands.volumes.quobyte.withUser

```ts
withUser(user)
```



### fn spec.commands.volumes.quobyte.withVolume

```ts
withVolume(volume)
```



## obj spec.commands.volumes.rbd



### fn spec.commands.volumes.rbd.withFsType

```ts
withFsType(fsType)
```



### fn spec.commands.volumes.rbd.withImage

```ts
withImage(image)
```



### fn spec.commands.volumes.rbd.withKeyring

```ts
withKeyring(keyring)
```



### fn spec.commands.volumes.rbd.withMonitors

```ts
withMonitors(monitors)
```



### fn spec.commands.volumes.rbd.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.volumes.rbd.withPool

```ts
withPool(pool)
```



### fn spec.commands.volumes.rbd.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.commands.volumes.rbd.withUser

```ts
withUser(user)
```



## obj spec.commands.volumes.rbd.secretRef



### fn spec.commands.volumes.rbd.secretRef.withName

```ts
withName(name)
```



## obj spec.commands.volumes.scaleIO



### fn spec.commands.volumes.scaleIO.withFsType

```ts
withFsType(fsType)
```



### fn spec.commands.volumes.scaleIO.withGateway

```ts
withGateway(gateway)
```



### fn spec.commands.volumes.scaleIO.withProtectionDomain

```ts
withProtectionDomain(protectionDomain)
```



### fn spec.commands.volumes.scaleIO.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.commands.volumes.scaleIO.withSslEnabled

```ts
withSslEnabled(sslEnabled)
```



### fn spec.commands.volumes.scaleIO.withStorageMode

```ts
withStorageMode(storageMode)
```



### fn spec.commands.volumes.scaleIO.withStoragePool

```ts
withStoragePool(storagePool)
```



### fn spec.commands.volumes.scaleIO.withSystem

```ts
withSystem(system)
```



### fn spec.commands.volumes.scaleIO.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.commands.volumes.scaleIO.secretRef



### fn spec.commands.volumes.scaleIO.secretRef.withName

```ts
withName(name)
```



## obj spec.commands.volumes.secret



### fn spec.commands.volumes.secret.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.commands.volumes.secret.withItems

```ts
withItems(items)
```



### fn spec.commands.volumes.secret.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.commands.volumes.secret.withOptional

```ts
withOptional(optional)
```



### fn spec.commands.volumes.secret.withSecretName

```ts
withSecretName(secretName)
```



## obj spec.commands.volumes.secret.items



### fn spec.commands.volumes.secret.items.withKey

```ts
withKey(key)
```



### fn spec.commands.volumes.secret.items.withMode

```ts
withMode(mode)
```



### fn spec.commands.volumes.secret.items.withPath

```ts
withPath(path)
```



## obj spec.commands.volumes.storageos



### fn spec.commands.volumes.storageos.withFsType

```ts
withFsType(fsType)
```



### fn spec.commands.volumes.storageos.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.commands.volumes.storageos.withVolumeName

```ts
withVolumeName(volumeName)
```



### fn spec.commands.volumes.storageos.withVolumeNamespace

```ts
withVolumeNamespace(volumeNamespace)
```



## obj spec.commands.volumes.storageos.secretRef



### fn spec.commands.volumes.storageos.secretRef.withName

```ts
withName(name)
```



## obj spec.commands.volumes.vsphereVolume



### fn spec.commands.volumes.vsphereVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.commands.volumes.vsphereVolume.withStoragePolicyID

```ts
withStoragePolicyID(storagePolicyID)
```



### fn spec.commands.volumes.vsphereVolume.withStoragePolicyName

```ts
withStoragePolicyName(storagePolicyName)
```



### fn spec.commands.volumes.vsphereVolume.withVolumePath

```ts
withVolumePath(volumePath)
```



## obj spec.containerSecurityContext



### fn spec.containerSecurityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```



### fn spec.containerSecurityContext.withPrivileged

```ts
withPrivileged(privileged)
```



### fn spec.containerSecurityContext.withProcMount

```ts
withProcMount(procMount)
```



### fn spec.containerSecurityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```



### fn spec.containerSecurityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.containerSecurityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.containerSecurityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



## obj spec.containerSecurityContext.appArmorProfile



### fn spec.containerSecurityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.containerSecurityContext.appArmorProfile.withType

```ts
withType(type)
```



## obj spec.containerSecurityContext.capabilities



### fn spec.containerSecurityContext.capabilities.withAdd

```ts
withAdd(add)
```



### fn spec.containerSecurityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```



**Note:** This function appends passed data to existing values

### fn spec.containerSecurityContext.capabilities.withDrop

```ts
withDrop(drop)
```



### fn spec.containerSecurityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```



**Note:** This function appends passed data to existing values

## obj spec.containerSecurityContext.seLinuxOptions



### fn spec.containerSecurityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.containerSecurityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.containerSecurityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.containerSecurityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.containerSecurityContext.seccompProfile



### fn spec.containerSecurityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.containerSecurityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.containerSecurityContext.windowsOptions



### fn spec.containerSecurityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.containerSecurityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.containerSecurityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.containerSecurityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.imagePullSecret



### fn spec.imagePullSecret.withName

```ts
withName(name)
```



## obj spec.securityContext



### fn spec.securityContext.withFsGroup

```ts
withFsGroup(fsGroup)
```



### fn spec.securityContext.withFsGroupChangePolicy

```ts
withFsGroupChangePolicy(fsGroupChangePolicy)
```



### fn spec.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



### fn spec.securityContext.withSupplementalGroups

```ts
withSupplementalGroups(supplementalGroups)
```



### fn spec.securityContext.withSupplementalGroupsMixin

```ts
withSupplementalGroupsMixin(supplementalGroups)
```



**Note:** This function appends passed data to existing values

### fn spec.securityContext.withSysctls

```ts
withSysctls(sysctls)
```



### fn spec.securityContext.withSysctlsMixin

```ts
withSysctlsMixin(sysctls)
```



**Note:** This function appends passed data to existing values

## obj spec.securityContext.appArmorProfile



### fn spec.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.securityContext.appArmorProfile.withType

```ts
withType(type)
```



## obj spec.securityContext.seLinuxOptions



### fn spec.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.securityContext.seccompProfile



### fn spec.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.securityContext.sysctls



### fn spec.securityContext.sysctls.withName

```ts
withName(name)
```



### fn spec.securityContext.sysctls.withValue

```ts
withValue(value)
```



## obj spec.securityContext.windowsOptions



### fn spec.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.tenant



### fn spec.tenant.withName

```ts
withName(name)
```



### fn spec.tenant.withNamespace

```ts
withNamespace(namespace)
```

