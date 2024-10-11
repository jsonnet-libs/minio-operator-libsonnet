---
permalink: /v5.0.15/minio/v2/tenant/
---

# minio.v2.tenant



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
* [`obj scheduler`](#obj-scheduler)
  * [`fn withName(name)`](#fn-schedulerwithname)
* [`obj spec`](#obj-spec)
  * [`fn withAdditionalVolumeMounts(additionalVolumeMounts)`](#fn-specwithadditionalvolumemounts)
  * [`fn withAdditionalVolumeMountsMixin(additionalVolumeMounts)`](#fn-specwithadditionalvolumemountsmixin)
  * [`fn withAdditionalVolumes(additionalVolumes)`](#fn-specwithadditionalvolumes)
  * [`fn withAdditionalVolumesMixin(additionalVolumes)`](#fn-specwithadditionalvolumesmixin)
  * [`fn withBuckets(buckets)`](#fn-specwithbuckets)
  * [`fn withBucketsMixin(buckets)`](#fn-specwithbucketsmixin)
  * [`fn withEnv(env)`](#fn-specwithenv)
  * [`fn withEnvMixin(env)`](#fn-specwithenvmixin)
  * [`fn withExternalCaCertSecret(externalCaCertSecret)`](#fn-specwithexternalcacertsecret)
  * [`fn withExternalCaCertSecretMixin(externalCaCertSecret)`](#fn-specwithexternalcacertsecretmixin)
  * [`fn withExternalCertSecret(externalCertSecret)`](#fn-specwithexternalcertsecret)
  * [`fn withExternalCertSecretMixin(externalCertSecret)`](#fn-specwithexternalcertsecretmixin)
  * [`fn withExternalClientCertSecrets(externalClientCertSecrets)`](#fn-specwithexternalclientcertsecrets)
  * [`fn withExternalClientCertSecretsMixin(externalClientCertSecrets)`](#fn-specwithexternalclientcertsecretsmixin)
  * [`fn withImage(image)`](#fn-specwithimage)
  * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-specwithimagepullpolicy)
  * [`fn withInitContainers(initContainers)`](#fn-specwithinitcontainers)
  * [`fn withInitContainersMixin(initContainers)`](#fn-specwithinitcontainersmixin)
  * [`fn withMountPath(mountPath)`](#fn-specwithmountpath)
  * [`fn withPodManagementPolicy(podManagementPolicy)`](#fn-specwithpodmanagementpolicy)
  * [`fn withPools(pools)`](#fn-specwithpools)
  * [`fn withPoolsMixin(pools)`](#fn-specwithpoolsmixin)
  * [`fn withPriorityClassName(priorityClassName)`](#fn-specwithpriorityclassname)
  * [`fn withPrometheusOperator(prometheusOperator)`](#fn-specwithprometheusoperator)
  * [`fn withRequestAutoCert(requestAutoCert)`](#fn-specwithrequestautocert)
  * [`fn withServiceAccountName(serviceAccountName)`](#fn-specwithserviceaccountname)
  * [`fn withSubPath(subPath)`](#fn-specwithsubpath)
  * [`fn withUsers(users)`](#fn-specwithusers)
  * [`fn withUsersMixin(users)`](#fn-specwithusersmixin)
  * [`obj spec.additionalVolumeMounts`](#obj-specadditionalvolumemounts)
    * [`fn withMountPath(mountPath)`](#fn-specadditionalvolumemountswithmountpath)
    * [`fn withMountPropagation(mountPropagation)`](#fn-specadditionalvolumemountswithmountpropagation)
    * [`fn withName(name)`](#fn-specadditionalvolumemountswithname)
    * [`fn withReadOnly(readOnly)`](#fn-specadditionalvolumemountswithreadonly)
    * [`fn withSubPath(subPath)`](#fn-specadditionalvolumemountswithsubpath)
    * [`fn withSubPathExpr(subPathExpr)`](#fn-specadditionalvolumemountswithsubpathexpr)
  * [`obj spec.additionalVolumes`](#obj-specadditionalvolumes)
    * [`fn withName(name)`](#fn-specadditionalvolumeswithname)
    * [`obj spec.additionalVolumes.awsElasticBlockStore`](#obj-specadditionalvolumesawselasticblockstore)
      * [`fn withFsType(fsType)`](#fn-specadditionalvolumesawselasticblockstorewithfstype)
      * [`fn withPartition(partition)`](#fn-specadditionalvolumesawselasticblockstorewithpartition)
      * [`fn withReadOnly(readOnly)`](#fn-specadditionalvolumesawselasticblockstorewithreadonly)
      * [`fn withVolumeID(volumeID)`](#fn-specadditionalvolumesawselasticblockstorewithvolumeid)
    * [`obj spec.additionalVolumes.azureDisk`](#obj-specadditionalvolumesazuredisk)
      * [`fn withCachingMode(cachingMode)`](#fn-specadditionalvolumesazurediskwithcachingmode)
      * [`fn withDiskName(diskName)`](#fn-specadditionalvolumesazurediskwithdiskname)
      * [`fn withDiskURI(diskURI)`](#fn-specadditionalvolumesazurediskwithdiskuri)
      * [`fn withFsType(fsType)`](#fn-specadditionalvolumesazurediskwithfstype)
      * [`fn withKind(kind)`](#fn-specadditionalvolumesazurediskwithkind)
      * [`fn withReadOnly(readOnly)`](#fn-specadditionalvolumesazurediskwithreadonly)
    * [`obj spec.additionalVolumes.azureFile`](#obj-specadditionalvolumesazurefile)
      * [`fn withReadOnly(readOnly)`](#fn-specadditionalvolumesazurefilewithreadonly)
      * [`fn withSecretName(secretName)`](#fn-specadditionalvolumesazurefilewithsecretname)
      * [`fn withShareName(shareName)`](#fn-specadditionalvolumesazurefilewithsharename)
    * [`obj spec.additionalVolumes.cephfs`](#obj-specadditionalvolumescephfs)
      * [`fn withMonitors(monitors)`](#fn-specadditionalvolumescephfswithmonitors)
      * [`fn withMonitorsMixin(monitors)`](#fn-specadditionalvolumescephfswithmonitorsmixin)
      * [`fn withPath(path)`](#fn-specadditionalvolumescephfswithpath)
      * [`fn withReadOnly(readOnly)`](#fn-specadditionalvolumescephfswithreadonly)
      * [`fn withSecretFile(secretFile)`](#fn-specadditionalvolumescephfswithsecretfile)
      * [`fn withUser(user)`](#fn-specadditionalvolumescephfswithuser)
      * [`obj spec.additionalVolumes.cephfs.secretRef`](#obj-specadditionalvolumescephfssecretref)
        * [`fn withName(name)`](#fn-specadditionalvolumescephfssecretrefwithname)
    * [`obj spec.additionalVolumes.cinder`](#obj-specadditionalvolumescinder)
      * [`fn withFsType(fsType)`](#fn-specadditionalvolumescinderwithfstype)
      * [`fn withReadOnly(readOnly)`](#fn-specadditionalvolumescinderwithreadonly)
      * [`fn withVolumeID(volumeID)`](#fn-specadditionalvolumescinderwithvolumeid)
      * [`obj spec.additionalVolumes.cinder.secretRef`](#obj-specadditionalvolumescindersecretref)
        * [`fn withName(name)`](#fn-specadditionalvolumescindersecretrefwithname)
    * [`obj spec.additionalVolumes.configMap`](#obj-specadditionalvolumesconfigmap)
      * [`fn withDefaultMode(defaultMode)`](#fn-specadditionalvolumesconfigmapwithdefaultmode)
      * [`fn withItems(items)`](#fn-specadditionalvolumesconfigmapwithitems)
      * [`fn withItemsMixin(items)`](#fn-specadditionalvolumesconfigmapwithitemsmixin)
      * [`fn withName(name)`](#fn-specadditionalvolumesconfigmapwithname)
      * [`fn withOptional(optional)`](#fn-specadditionalvolumesconfigmapwithoptional)
      * [`obj spec.additionalVolumes.configMap.items`](#obj-specadditionalvolumesconfigmapitems)
        * [`fn withKey(key)`](#fn-specadditionalvolumesconfigmapitemswithkey)
        * [`fn withMode(mode)`](#fn-specadditionalvolumesconfigmapitemswithmode)
        * [`fn withPath(path)`](#fn-specadditionalvolumesconfigmapitemswithpath)
    * [`obj spec.additionalVolumes.csi`](#obj-specadditionalvolumescsi)
      * [`fn withDriver(driver)`](#fn-specadditionalvolumescsiwithdriver)
      * [`fn withFsType(fsType)`](#fn-specadditionalvolumescsiwithfstype)
      * [`fn withReadOnly(readOnly)`](#fn-specadditionalvolumescsiwithreadonly)
      * [`fn withVolumeAttributes(volumeAttributes)`](#fn-specadditionalvolumescsiwithvolumeattributes)
      * [`fn withVolumeAttributesMixin(volumeAttributes)`](#fn-specadditionalvolumescsiwithvolumeattributesmixin)
      * [`obj spec.additionalVolumes.csi.nodePublishSecretRef`](#obj-specadditionalvolumescsinodepublishsecretref)
        * [`fn withName(name)`](#fn-specadditionalvolumescsinodepublishsecretrefwithname)
    * [`obj spec.additionalVolumes.downwardAPI`](#obj-specadditionalvolumesdownwardapi)
      * [`fn withDefaultMode(defaultMode)`](#fn-specadditionalvolumesdownwardapiwithdefaultmode)
      * [`fn withItems(items)`](#fn-specadditionalvolumesdownwardapiwithitems)
      * [`fn withItemsMixin(items)`](#fn-specadditionalvolumesdownwardapiwithitemsmixin)
      * [`obj spec.additionalVolumes.downwardAPI.items`](#obj-specadditionalvolumesdownwardapiitems)
        * [`fn withMode(mode)`](#fn-specadditionalvolumesdownwardapiitemswithmode)
        * [`fn withPath(path)`](#fn-specadditionalvolumesdownwardapiitemswithpath)
        * [`obj spec.additionalVolumes.downwardAPI.items.fieldRef`](#obj-specadditionalvolumesdownwardapiitemsfieldref)
          * [`fn withApiVersion(apiVersion)`](#fn-specadditionalvolumesdownwardapiitemsfieldrefwithapiversion)
          * [`fn withFieldPath(fieldPath)`](#fn-specadditionalvolumesdownwardapiitemsfieldrefwithfieldpath)
        * [`obj spec.additionalVolumes.downwardAPI.items.resourceFieldRef`](#obj-specadditionalvolumesdownwardapiitemsresourcefieldref)
          * [`fn withContainerName(containerName)`](#fn-specadditionalvolumesdownwardapiitemsresourcefieldrefwithcontainername)
          * [`fn withDivisor(divisor)`](#fn-specadditionalvolumesdownwardapiitemsresourcefieldrefwithdivisor)
          * [`fn withResource(resource)`](#fn-specadditionalvolumesdownwardapiitemsresourcefieldrefwithresource)
    * [`obj spec.additionalVolumes.emptyDir`](#obj-specadditionalvolumesemptydir)
      * [`fn withMedium(medium)`](#fn-specadditionalvolumesemptydirwithmedium)
      * [`fn withSizeLimit(sizeLimit)`](#fn-specadditionalvolumesemptydirwithsizelimit)
    * [`obj spec.additionalVolumes.ephemeral`](#obj-specadditionalvolumesephemeral)
      * [`obj spec.additionalVolumes.ephemeral.volumeClaimTemplate`](#obj-specadditionalvolumesephemeralvolumeclaimtemplate)
        * [`obj spec.additionalVolumes.ephemeral.volumeClaimTemplate.metadata`](#obj-specadditionalvolumesephemeralvolumeclaimtemplatemetadata)
          * [`fn withAnnotations(annotations)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatemetadatawithannotations)
          * [`fn withAnnotationsMixin(annotations)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatemetadatawithannotationsmixin)
          * [`fn withFinalizers(finalizers)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatemetadatawithfinalizers)
          * [`fn withFinalizersMixin(finalizers)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatemetadatawithfinalizersmixin)
          * [`fn withLabels(labels)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatemetadatawithlabels)
          * [`fn withLabelsMixin(labels)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatemetadatawithlabelsmixin)
          * [`fn withName(name)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatemetadatawithname)
          * [`fn withNamespace(namespace)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatemetadatawithnamespace)
        * [`obj spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec`](#obj-specadditionalvolumesephemeralvolumeclaimtemplatespec)
          * [`fn withAccessModes(accessModes)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecwithaccessmodes)
          * [`fn withAccessModesMixin(accessModes)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecwithaccessmodesmixin)
          * [`fn withStorageClassName(storageClassName)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecwithstorageclassname)
          * [`fn withVolumeAttributesClassName(volumeAttributesClassName)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecwithvolumeattributesclassname)
          * [`fn withVolumeMode(volumeMode)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecwithvolumemode)
          * [`fn withVolumeName(volumeName)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecwithvolumename)
          * [`obj spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.dataSource`](#obj-specadditionalvolumesephemeralvolumeclaimtemplatespecdatasource)
            * [`fn withApiGroup(apiGroup)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecdatasourcewithapigroup)
            * [`fn withKind(kind)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecdatasourcewithkind)
            * [`fn withName(name)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecdatasourcewithname)
          * [`obj spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef`](#obj-specadditionalvolumesephemeralvolumeclaimtemplatespecdatasourceref)
            * [`fn withApiGroup(apiGroup)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithapigroup)
            * [`fn withKind(kind)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithkind)
            * [`fn withName(name)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithname)
            * [`fn withNamespace(namespace)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithnamespace)
          * [`obj spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.resources`](#obj-specadditionalvolumesephemeralvolumeclaimtemplatespecresources)
            * [`fn withLimits(limits)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecresourceswithlimits)
            * [`fn withLimitsMixin(limits)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecresourceswithlimitsmixin)
            * [`fn withRequests(requests)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecresourceswithrequests)
            * [`fn withRequestsMixin(requests)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecresourceswithrequestsmixin)
          * [`obj spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.selector`](#obj-specadditionalvolumesephemeralvolumeclaimtemplatespecselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabelsmixin)
            * [`obj spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions`](#obj-specadditionalvolumesephemeralvolumeclaimtemplatespecselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specadditionalvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvaluesmixin)
    * [`obj spec.additionalVolumes.fc`](#obj-specadditionalvolumesfc)
      * [`fn withFsType(fsType)`](#fn-specadditionalvolumesfcwithfstype)
      * [`fn withLun(lun)`](#fn-specadditionalvolumesfcwithlun)
      * [`fn withReadOnly(readOnly)`](#fn-specadditionalvolumesfcwithreadonly)
      * [`fn withTargetWWNs(targetWWNs)`](#fn-specadditionalvolumesfcwithtargetwwns)
      * [`fn withTargetWWNsMixin(targetWWNs)`](#fn-specadditionalvolumesfcwithtargetwwnsmixin)
      * [`fn withWwids(wwids)`](#fn-specadditionalvolumesfcwithwwids)
      * [`fn withWwidsMixin(wwids)`](#fn-specadditionalvolumesfcwithwwidsmixin)
    * [`obj spec.additionalVolumes.flexVolume`](#obj-specadditionalvolumesflexvolume)
      * [`fn withDriver(driver)`](#fn-specadditionalvolumesflexvolumewithdriver)
      * [`fn withFsType(fsType)`](#fn-specadditionalvolumesflexvolumewithfstype)
      * [`fn withOptions(options)`](#fn-specadditionalvolumesflexvolumewithoptions)
      * [`fn withOptionsMixin(options)`](#fn-specadditionalvolumesflexvolumewithoptionsmixin)
      * [`fn withReadOnly(readOnly)`](#fn-specadditionalvolumesflexvolumewithreadonly)
      * [`obj spec.additionalVolumes.flexVolume.secretRef`](#obj-specadditionalvolumesflexvolumesecretref)
        * [`fn withName(name)`](#fn-specadditionalvolumesflexvolumesecretrefwithname)
    * [`obj spec.additionalVolumes.flocker`](#obj-specadditionalvolumesflocker)
      * [`fn withDatasetName(datasetName)`](#fn-specadditionalvolumesflockerwithdatasetname)
      * [`fn withDatasetUUID(datasetUUID)`](#fn-specadditionalvolumesflockerwithdatasetuuid)
    * [`obj spec.additionalVolumes.gcePersistentDisk`](#obj-specadditionalvolumesgcepersistentdisk)
      * [`fn withFsType(fsType)`](#fn-specadditionalvolumesgcepersistentdiskwithfstype)
      * [`fn withPartition(partition)`](#fn-specadditionalvolumesgcepersistentdiskwithpartition)
      * [`fn withPdName(pdName)`](#fn-specadditionalvolumesgcepersistentdiskwithpdname)
      * [`fn withReadOnly(readOnly)`](#fn-specadditionalvolumesgcepersistentdiskwithreadonly)
    * [`obj spec.additionalVolumes.gitRepo`](#obj-specadditionalvolumesgitrepo)
      * [`fn withDirectory(directory)`](#fn-specadditionalvolumesgitrepowithdirectory)
      * [`fn withRepository(repository)`](#fn-specadditionalvolumesgitrepowithrepository)
      * [`fn withRevision(revision)`](#fn-specadditionalvolumesgitrepowithrevision)
    * [`obj spec.additionalVolumes.glusterfs`](#obj-specadditionalvolumesglusterfs)
      * [`fn withEndpoints(endpoints)`](#fn-specadditionalvolumesglusterfswithendpoints)
      * [`fn withPath(path)`](#fn-specadditionalvolumesglusterfswithpath)
      * [`fn withReadOnly(readOnly)`](#fn-specadditionalvolumesglusterfswithreadonly)
    * [`obj spec.additionalVolumes.hostPath`](#obj-specadditionalvolumeshostpath)
      * [`fn withPath(path)`](#fn-specadditionalvolumeshostpathwithpath)
      * [`fn withType(type)`](#fn-specadditionalvolumeshostpathwithtype)
    * [`obj spec.additionalVolumes.iscsi`](#obj-specadditionalvolumesiscsi)
      * [`fn withChapAuthDiscovery(chapAuthDiscovery)`](#fn-specadditionalvolumesiscsiwithchapauthdiscovery)
      * [`fn withChapAuthSession(chapAuthSession)`](#fn-specadditionalvolumesiscsiwithchapauthsession)
      * [`fn withFsType(fsType)`](#fn-specadditionalvolumesiscsiwithfstype)
      * [`fn withInitiatorName(initiatorName)`](#fn-specadditionalvolumesiscsiwithinitiatorname)
      * [`fn withIqn(iqn)`](#fn-specadditionalvolumesiscsiwithiqn)
      * [`fn withIscsiInterface(iscsiInterface)`](#fn-specadditionalvolumesiscsiwithiscsiinterface)
      * [`fn withLun(lun)`](#fn-specadditionalvolumesiscsiwithlun)
      * [`fn withPortals(portals)`](#fn-specadditionalvolumesiscsiwithportals)
      * [`fn withPortalsMixin(portals)`](#fn-specadditionalvolumesiscsiwithportalsmixin)
      * [`fn withReadOnly(readOnly)`](#fn-specadditionalvolumesiscsiwithreadonly)
      * [`fn withTargetPortal(targetPortal)`](#fn-specadditionalvolumesiscsiwithtargetportal)
      * [`obj spec.additionalVolumes.iscsi.secretRef`](#obj-specadditionalvolumesiscsisecretref)
        * [`fn withName(name)`](#fn-specadditionalvolumesiscsisecretrefwithname)
    * [`obj spec.additionalVolumes.nfs`](#obj-specadditionalvolumesnfs)
      * [`fn withPath(path)`](#fn-specadditionalvolumesnfswithpath)
      * [`fn withReadOnly(readOnly)`](#fn-specadditionalvolumesnfswithreadonly)
      * [`fn withServer(server)`](#fn-specadditionalvolumesnfswithserver)
    * [`obj spec.additionalVolumes.persistentVolumeClaim`](#obj-specadditionalvolumespersistentvolumeclaim)
      * [`fn withClaimName(claimName)`](#fn-specadditionalvolumespersistentvolumeclaimwithclaimname)
      * [`fn withReadOnly(readOnly)`](#fn-specadditionalvolumespersistentvolumeclaimwithreadonly)
    * [`obj spec.additionalVolumes.photonPersistentDisk`](#obj-specadditionalvolumesphotonpersistentdisk)
      * [`fn withFsType(fsType)`](#fn-specadditionalvolumesphotonpersistentdiskwithfstype)
      * [`fn withPdID(pdID)`](#fn-specadditionalvolumesphotonpersistentdiskwithpdid)
    * [`obj spec.additionalVolumes.portworxVolume`](#obj-specadditionalvolumesportworxvolume)
      * [`fn withFsType(fsType)`](#fn-specadditionalvolumesportworxvolumewithfstype)
      * [`fn withReadOnly(readOnly)`](#fn-specadditionalvolumesportworxvolumewithreadonly)
      * [`fn withVolumeID(volumeID)`](#fn-specadditionalvolumesportworxvolumewithvolumeid)
    * [`obj spec.additionalVolumes.projected`](#obj-specadditionalvolumesprojected)
      * [`fn withDefaultMode(defaultMode)`](#fn-specadditionalvolumesprojectedwithdefaultmode)
      * [`fn withSources(sources)`](#fn-specadditionalvolumesprojectedwithsources)
      * [`fn withSourcesMixin(sources)`](#fn-specadditionalvolumesprojectedwithsourcesmixin)
      * [`obj spec.additionalVolumes.projected.sources`](#obj-specadditionalvolumesprojectedsources)
        * [`obj spec.additionalVolumes.projected.sources.clusterTrustBundle`](#obj-specadditionalvolumesprojectedsourcesclustertrustbundle)
          * [`fn withName(name)`](#fn-specadditionalvolumesprojectedsourcesclustertrustbundlewithname)
          * [`fn withOptional(optional)`](#fn-specadditionalvolumesprojectedsourcesclustertrustbundlewithoptional)
          * [`fn withPath(path)`](#fn-specadditionalvolumesprojectedsourcesclustertrustbundlewithpath)
          * [`fn withSignerName(signerName)`](#fn-specadditionalvolumesprojectedsourcesclustertrustbundlewithsignername)
          * [`obj spec.additionalVolumes.projected.sources.clusterTrustBundle.labelSelector`](#obj-specadditionalvolumesprojectedsourcesclustertrustbundlelabelselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specadditionalvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specadditionalvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specadditionalvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specadditionalvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabelsmixin)
            * [`obj spec.additionalVolumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions`](#obj-specadditionalvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specadditionalvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specadditionalvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specadditionalvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specadditionalvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvaluesmixin)
        * [`obj spec.additionalVolumes.projected.sources.configMap`](#obj-specadditionalvolumesprojectedsourcesconfigmap)
          * [`fn withItems(items)`](#fn-specadditionalvolumesprojectedsourcesconfigmapwithitems)
          * [`fn withItemsMixin(items)`](#fn-specadditionalvolumesprojectedsourcesconfigmapwithitemsmixin)
          * [`fn withName(name)`](#fn-specadditionalvolumesprojectedsourcesconfigmapwithname)
          * [`fn withOptional(optional)`](#fn-specadditionalvolumesprojectedsourcesconfigmapwithoptional)
          * [`obj spec.additionalVolumes.projected.sources.configMap.items`](#obj-specadditionalvolumesprojectedsourcesconfigmapitems)
            * [`fn withKey(key)`](#fn-specadditionalvolumesprojectedsourcesconfigmapitemswithkey)
            * [`fn withMode(mode)`](#fn-specadditionalvolumesprojectedsourcesconfigmapitemswithmode)
            * [`fn withPath(path)`](#fn-specadditionalvolumesprojectedsourcesconfigmapitemswithpath)
        * [`obj spec.additionalVolumes.projected.sources.downwardAPI`](#obj-specadditionalvolumesprojectedsourcesdownwardapi)
          * [`fn withItems(items)`](#fn-specadditionalvolumesprojectedsourcesdownwardapiwithitems)
          * [`fn withItemsMixin(items)`](#fn-specadditionalvolumesprojectedsourcesdownwardapiwithitemsmixin)
          * [`obj spec.additionalVolumes.projected.sources.downwardAPI.items`](#obj-specadditionalvolumesprojectedsourcesdownwardapiitems)
            * [`fn withMode(mode)`](#fn-specadditionalvolumesprojectedsourcesdownwardapiitemswithmode)
            * [`fn withPath(path)`](#fn-specadditionalvolumesprojectedsourcesdownwardapiitemswithpath)
            * [`obj spec.additionalVolumes.projected.sources.downwardAPI.items.fieldRef`](#obj-specadditionalvolumesprojectedsourcesdownwardapiitemsfieldref)
              * [`fn withApiVersion(apiVersion)`](#fn-specadditionalvolumesprojectedsourcesdownwardapiitemsfieldrefwithapiversion)
              * [`fn withFieldPath(fieldPath)`](#fn-specadditionalvolumesprojectedsourcesdownwardapiitemsfieldrefwithfieldpath)
            * [`obj spec.additionalVolumes.projected.sources.downwardAPI.items.resourceFieldRef`](#obj-specadditionalvolumesprojectedsourcesdownwardapiitemsresourcefieldref)
              * [`fn withContainerName(containerName)`](#fn-specadditionalvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithcontainername)
              * [`fn withDivisor(divisor)`](#fn-specadditionalvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithdivisor)
              * [`fn withResource(resource)`](#fn-specadditionalvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithresource)
        * [`obj spec.additionalVolumes.projected.sources.secret`](#obj-specadditionalvolumesprojectedsourcessecret)
          * [`fn withItems(items)`](#fn-specadditionalvolumesprojectedsourcessecretwithitems)
          * [`fn withItemsMixin(items)`](#fn-specadditionalvolumesprojectedsourcessecretwithitemsmixin)
          * [`fn withName(name)`](#fn-specadditionalvolumesprojectedsourcessecretwithname)
          * [`fn withOptional(optional)`](#fn-specadditionalvolumesprojectedsourcessecretwithoptional)
          * [`obj spec.additionalVolumes.projected.sources.secret.items`](#obj-specadditionalvolumesprojectedsourcessecretitems)
            * [`fn withKey(key)`](#fn-specadditionalvolumesprojectedsourcessecretitemswithkey)
            * [`fn withMode(mode)`](#fn-specadditionalvolumesprojectedsourcessecretitemswithmode)
            * [`fn withPath(path)`](#fn-specadditionalvolumesprojectedsourcessecretitemswithpath)
        * [`obj spec.additionalVolumes.projected.sources.serviceAccountToken`](#obj-specadditionalvolumesprojectedsourcesserviceaccounttoken)
          * [`fn withAudience(audience)`](#fn-specadditionalvolumesprojectedsourcesserviceaccounttokenwithaudience)
          * [`fn withExpirationSeconds(expirationSeconds)`](#fn-specadditionalvolumesprojectedsourcesserviceaccounttokenwithexpirationseconds)
          * [`fn withPath(path)`](#fn-specadditionalvolumesprojectedsourcesserviceaccounttokenwithpath)
    * [`obj spec.additionalVolumes.quobyte`](#obj-specadditionalvolumesquobyte)
      * [`fn withGroup(group)`](#fn-specadditionalvolumesquobytewithgroup)
      * [`fn withReadOnly(readOnly)`](#fn-specadditionalvolumesquobytewithreadonly)
      * [`fn withRegistry(registry)`](#fn-specadditionalvolumesquobytewithregistry)
      * [`fn withTenant(tenant)`](#fn-specadditionalvolumesquobytewithtenant)
      * [`fn withUser(user)`](#fn-specadditionalvolumesquobytewithuser)
      * [`fn withVolume(volume)`](#fn-specadditionalvolumesquobytewithvolume)
    * [`obj spec.additionalVolumes.rbd`](#obj-specadditionalvolumesrbd)
      * [`fn withFsType(fsType)`](#fn-specadditionalvolumesrbdwithfstype)
      * [`fn withImage(image)`](#fn-specadditionalvolumesrbdwithimage)
      * [`fn withKeyring(keyring)`](#fn-specadditionalvolumesrbdwithkeyring)
      * [`fn withMonitors(monitors)`](#fn-specadditionalvolumesrbdwithmonitors)
      * [`fn withMonitorsMixin(monitors)`](#fn-specadditionalvolumesrbdwithmonitorsmixin)
      * [`fn withPool(pool)`](#fn-specadditionalvolumesrbdwithpool)
      * [`fn withReadOnly(readOnly)`](#fn-specadditionalvolumesrbdwithreadonly)
      * [`fn withUser(user)`](#fn-specadditionalvolumesrbdwithuser)
      * [`obj spec.additionalVolumes.rbd.secretRef`](#obj-specadditionalvolumesrbdsecretref)
        * [`fn withName(name)`](#fn-specadditionalvolumesrbdsecretrefwithname)
    * [`obj spec.additionalVolumes.scaleIO`](#obj-specadditionalvolumesscaleio)
      * [`fn withFsType(fsType)`](#fn-specadditionalvolumesscaleiowithfstype)
      * [`fn withGateway(gateway)`](#fn-specadditionalvolumesscaleiowithgateway)
      * [`fn withProtectionDomain(protectionDomain)`](#fn-specadditionalvolumesscaleiowithprotectiondomain)
      * [`fn withReadOnly(readOnly)`](#fn-specadditionalvolumesscaleiowithreadonly)
      * [`fn withSslEnabled(sslEnabled)`](#fn-specadditionalvolumesscaleiowithsslenabled)
      * [`fn withStorageMode(storageMode)`](#fn-specadditionalvolumesscaleiowithstoragemode)
      * [`fn withStoragePool(storagePool)`](#fn-specadditionalvolumesscaleiowithstoragepool)
      * [`fn withSystem(system)`](#fn-specadditionalvolumesscaleiowithsystem)
      * [`fn withVolumeName(volumeName)`](#fn-specadditionalvolumesscaleiowithvolumename)
      * [`obj spec.additionalVolumes.scaleIO.secretRef`](#obj-specadditionalvolumesscaleiosecretref)
        * [`fn withName(name)`](#fn-specadditionalvolumesscaleiosecretrefwithname)
    * [`obj spec.additionalVolumes.secret`](#obj-specadditionalvolumessecret)
      * [`fn withDefaultMode(defaultMode)`](#fn-specadditionalvolumessecretwithdefaultmode)
      * [`fn withItems(items)`](#fn-specadditionalvolumessecretwithitems)
      * [`fn withItemsMixin(items)`](#fn-specadditionalvolumessecretwithitemsmixin)
      * [`fn withOptional(optional)`](#fn-specadditionalvolumessecretwithoptional)
      * [`fn withSecretName(secretName)`](#fn-specadditionalvolumessecretwithsecretname)
      * [`obj spec.additionalVolumes.secret.items`](#obj-specadditionalvolumessecretitems)
        * [`fn withKey(key)`](#fn-specadditionalvolumessecretitemswithkey)
        * [`fn withMode(mode)`](#fn-specadditionalvolumessecretitemswithmode)
        * [`fn withPath(path)`](#fn-specadditionalvolumessecretitemswithpath)
    * [`obj spec.additionalVolumes.storageos`](#obj-specadditionalvolumesstorageos)
      * [`fn withFsType(fsType)`](#fn-specadditionalvolumesstorageoswithfstype)
      * [`fn withReadOnly(readOnly)`](#fn-specadditionalvolumesstorageoswithreadonly)
      * [`fn withVolumeName(volumeName)`](#fn-specadditionalvolumesstorageoswithvolumename)
      * [`fn withVolumeNamespace(volumeNamespace)`](#fn-specadditionalvolumesstorageoswithvolumenamespace)
      * [`obj spec.additionalVolumes.storageos.secretRef`](#obj-specadditionalvolumesstorageossecretref)
        * [`fn withName(name)`](#fn-specadditionalvolumesstorageossecretrefwithname)
    * [`obj spec.additionalVolumes.vsphereVolume`](#obj-specadditionalvolumesvspherevolume)
      * [`fn withFsType(fsType)`](#fn-specadditionalvolumesvspherevolumewithfstype)
      * [`fn withStoragePolicyID(storagePolicyID)`](#fn-specadditionalvolumesvspherevolumewithstoragepolicyid)
      * [`fn withStoragePolicyName(storagePolicyName)`](#fn-specadditionalvolumesvspherevolumewithstoragepolicyname)
      * [`fn withVolumePath(volumePath)`](#fn-specadditionalvolumesvspherevolumewithvolumepath)
  * [`obj spec.buckets`](#obj-specbuckets)
    * [`fn withName(name)`](#fn-specbucketswithname)
    * [`fn withObjectLock(objectLock)`](#fn-specbucketswithobjectlock)
    * [`fn withRegion(region)`](#fn-specbucketswithregion)
  * [`obj spec.certConfig`](#obj-speccertconfig)
    * [`fn withCommonName(commonName)`](#fn-speccertconfigwithcommonname)
    * [`fn withDnsNames(dnsNames)`](#fn-speccertconfigwithdnsnames)
    * [`fn withDnsNamesMixin(dnsNames)`](#fn-speccertconfigwithdnsnamesmixin)
    * [`fn withOrganizationName(organizationName)`](#fn-speccertconfigwithorganizationname)
    * [`fn withOrganizationNameMixin(organizationName)`](#fn-speccertconfigwithorganizationnamemixin)
  * [`obj spec.configuration`](#obj-specconfiguration)
    * [`fn withName(name)`](#fn-specconfigurationwithname)
  * [`obj spec.credsSecret`](#obj-speccredssecret)
    * [`fn withName(name)`](#fn-speccredssecretwithname)
  * [`obj spec.env`](#obj-specenv)
    * [`fn withName(name)`](#fn-specenvwithname)
    * [`fn withValue(value)`](#fn-specenvwithvalue)
    * [`obj spec.env.valueFrom`](#obj-specenvvaluefrom)
      * [`obj spec.env.valueFrom.configMapKeyRef`](#obj-specenvvaluefromconfigmapkeyref)
        * [`fn withKey(key)`](#fn-specenvvaluefromconfigmapkeyrefwithkey)
        * [`fn withName(name)`](#fn-specenvvaluefromconfigmapkeyrefwithname)
        * [`fn withOptional(optional)`](#fn-specenvvaluefromconfigmapkeyrefwithoptional)
      * [`obj spec.env.valueFrom.fieldRef`](#obj-specenvvaluefromfieldref)
        * [`fn withApiVersion(apiVersion)`](#fn-specenvvaluefromfieldrefwithapiversion)
        * [`fn withFieldPath(fieldPath)`](#fn-specenvvaluefromfieldrefwithfieldpath)
      * [`obj spec.env.valueFrom.resourceFieldRef`](#obj-specenvvaluefromresourcefieldref)
        * [`fn withContainerName(containerName)`](#fn-specenvvaluefromresourcefieldrefwithcontainername)
        * [`fn withDivisor(divisor)`](#fn-specenvvaluefromresourcefieldrefwithdivisor)
        * [`fn withResource(resource)`](#fn-specenvvaluefromresourcefieldrefwithresource)
      * [`obj spec.env.valueFrom.secretKeyRef`](#obj-specenvvaluefromsecretkeyref)
        * [`fn withKey(key)`](#fn-specenvvaluefromsecretkeyrefwithkey)
        * [`fn withName(name)`](#fn-specenvvaluefromsecretkeyrefwithname)
        * [`fn withOptional(optional)`](#fn-specenvvaluefromsecretkeyrefwithoptional)
  * [`obj spec.exposeServices`](#obj-specexposeservices)
    * [`fn withConsole(console)`](#fn-specexposeserviceswithconsole)
    * [`fn withMinio(minio)`](#fn-specexposeserviceswithminio)
  * [`obj spec.externalCaCertSecret`](#obj-specexternalcacertsecret)
    * [`fn withName(name)`](#fn-specexternalcacertsecretwithname)
    * [`fn withType(type)`](#fn-specexternalcacertsecretwithtype)
  * [`obj spec.externalCertSecret`](#obj-specexternalcertsecret)
    * [`fn withName(name)`](#fn-specexternalcertsecretwithname)
    * [`fn withType(type)`](#fn-specexternalcertsecretwithtype)
  * [`obj spec.externalClientCertSecret`](#obj-specexternalclientcertsecret)
    * [`fn withName(name)`](#fn-specexternalclientcertsecretwithname)
    * [`fn withType(type)`](#fn-specexternalclientcertsecretwithtype)
  * [`obj spec.externalClientCertSecrets`](#obj-specexternalclientcertsecrets)
    * [`fn withName(name)`](#fn-specexternalclientcertsecretswithname)
    * [`fn withType(type)`](#fn-specexternalclientcertsecretswithtype)
  * [`obj spec.features`](#obj-specfeatures)
    * [`fn withBucketDNS(bucketDNS)`](#fn-specfeatureswithbucketdns)
    * [`fn withEnableSFTP(enableSFTP)`](#fn-specfeatureswithenablesftp)
    * [`obj spec.features.domains`](#obj-specfeaturesdomains)
      * [`fn withConsole(console)`](#fn-specfeaturesdomainswithconsole)
      * [`fn withMinio(minio)`](#fn-specfeaturesdomainswithminio)
      * [`fn withMinioMixin(minio)`](#fn-specfeaturesdomainswithminiomixin)
  * [`obj spec.imagePullSecret`](#obj-specimagepullsecret)
    * [`fn withName(name)`](#fn-specimagepullsecretwithname)
  * [`obj spec.initContainers`](#obj-specinitcontainers)
    * [`fn withArgs(args)`](#fn-specinitcontainerswithargs)
    * [`fn withArgsMixin(args)`](#fn-specinitcontainerswithargsmixin)
    * [`fn withCommand(command)`](#fn-specinitcontainerswithcommand)
    * [`fn withCommandMixin(command)`](#fn-specinitcontainerswithcommandmixin)
    * [`fn withEnv(env)`](#fn-specinitcontainerswithenv)
    * [`fn withEnvFrom(envFrom)`](#fn-specinitcontainerswithenvfrom)
    * [`fn withEnvFromMixin(envFrom)`](#fn-specinitcontainerswithenvfrommixin)
    * [`fn withEnvMixin(env)`](#fn-specinitcontainerswithenvmixin)
    * [`fn withImage(image)`](#fn-specinitcontainerswithimage)
    * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-specinitcontainerswithimagepullpolicy)
    * [`fn withName(name)`](#fn-specinitcontainerswithname)
    * [`fn withPorts(ports)`](#fn-specinitcontainerswithports)
    * [`fn withPortsMixin(ports)`](#fn-specinitcontainerswithportsmixin)
    * [`fn withResizePolicy(resizePolicy)`](#fn-specinitcontainerswithresizepolicy)
    * [`fn withResizePolicyMixin(resizePolicy)`](#fn-specinitcontainerswithresizepolicymixin)
    * [`fn withRestartPolicy(restartPolicy)`](#fn-specinitcontainerswithrestartpolicy)
    * [`fn withStdin(stdin)`](#fn-specinitcontainerswithstdin)
    * [`fn withStdinOnce(stdinOnce)`](#fn-specinitcontainerswithstdinonce)
    * [`fn withTerminationMessagePath(terminationMessagePath)`](#fn-specinitcontainerswithterminationmessagepath)
    * [`fn withTerminationMessagePolicy(terminationMessagePolicy)`](#fn-specinitcontainerswithterminationmessagepolicy)
    * [`fn withTty(tty)`](#fn-specinitcontainerswithtty)
    * [`fn withVolumeDevices(volumeDevices)`](#fn-specinitcontainerswithvolumedevices)
    * [`fn withVolumeDevicesMixin(volumeDevices)`](#fn-specinitcontainerswithvolumedevicesmixin)
    * [`fn withVolumeMounts(volumeMounts)`](#fn-specinitcontainerswithvolumemounts)
    * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specinitcontainerswithvolumemountsmixin)
    * [`fn withWorkingDir(workingDir)`](#fn-specinitcontainerswithworkingdir)
    * [`obj spec.initContainers.env`](#obj-specinitcontainersenv)
      * [`fn withName(name)`](#fn-specinitcontainersenvwithname)
      * [`fn withValue(value)`](#fn-specinitcontainersenvwithvalue)
      * [`obj spec.initContainers.env.valueFrom`](#obj-specinitcontainersenvvaluefrom)
        * [`obj spec.initContainers.env.valueFrom.configMapKeyRef`](#obj-specinitcontainersenvvaluefromconfigmapkeyref)
          * [`fn withKey(key)`](#fn-specinitcontainersenvvaluefromconfigmapkeyrefwithkey)
          * [`fn withName(name)`](#fn-specinitcontainersenvvaluefromconfigmapkeyrefwithname)
          * [`fn withOptional(optional)`](#fn-specinitcontainersenvvaluefromconfigmapkeyrefwithoptional)
        * [`obj spec.initContainers.env.valueFrom.fieldRef`](#obj-specinitcontainersenvvaluefromfieldref)
          * [`fn withApiVersion(apiVersion)`](#fn-specinitcontainersenvvaluefromfieldrefwithapiversion)
          * [`fn withFieldPath(fieldPath)`](#fn-specinitcontainersenvvaluefromfieldrefwithfieldpath)
        * [`obj spec.initContainers.env.valueFrom.resourceFieldRef`](#obj-specinitcontainersenvvaluefromresourcefieldref)
          * [`fn withContainerName(containerName)`](#fn-specinitcontainersenvvaluefromresourcefieldrefwithcontainername)
          * [`fn withDivisor(divisor)`](#fn-specinitcontainersenvvaluefromresourcefieldrefwithdivisor)
          * [`fn withResource(resource)`](#fn-specinitcontainersenvvaluefromresourcefieldrefwithresource)
        * [`obj spec.initContainers.env.valueFrom.secretKeyRef`](#obj-specinitcontainersenvvaluefromsecretkeyref)
          * [`fn withKey(key)`](#fn-specinitcontainersenvvaluefromsecretkeyrefwithkey)
          * [`fn withName(name)`](#fn-specinitcontainersenvvaluefromsecretkeyrefwithname)
          * [`fn withOptional(optional)`](#fn-specinitcontainersenvvaluefromsecretkeyrefwithoptional)
    * [`obj spec.initContainers.envFrom`](#obj-specinitcontainersenvfrom)
      * [`fn withPrefix(prefix)`](#fn-specinitcontainersenvfromwithprefix)
      * [`obj spec.initContainers.envFrom.configMapRef`](#obj-specinitcontainersenvfromconfigmapref)
        * [`fn withName(name)`](#fn-specinitcontainersenvfromconfigmaprefwithname)
        * [`fn withOptional(optional)`](#fn-specinitcontainersenvfromconfigmaprefwithoptional)
      * [`obj spec.initContainers.envFrom.secretRef`](#obj-specinitcontainersenvfromsecretref)
        * [`fn withName(name)`](#fn-specinitcontainersenvfromsecretrefwithname)
        * [`fn withOptional(optional)`](#fn-specinitcontainersenvfromsecretrefwithoptional)
    * [`obj spec.initContainers.lifecycle`](#obj-specinitcontainerslifecycle)
      * [`obj spec.initContainers.lifecycle.postStart`](#obj-specinitcontainerslifecyclepoststart)
        * [`obj spec.initContainers.lifecycle.postStart.exec`](#obj-specinitcontainerslifecyclepoststartexec)
          * [`fn withCommand(command)`](#fn-specinitcontainerslifecyclepoststartexecwithcommand)
          * [`fn withCommandMixin(command)`](#fn-specinitcontainerslifecyclepoststartexecwithcommandmixin)
        * [`obj spec.initContainers.lifecycle.postStart.httpGet`](#obj-specinitcontainerslifecyclepoststarthttpget)
          * [`fn withHost(host)`](#fn-specinitcontainerslifecyclepoststarthttpgetwithhost)
          * [`fn withHttpHeaders(httpHeaders)`](#fn-specinitcontainerslifecyclepoststarthttpgetwithhttpheaders)
          * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specinitcontainerslifecyclepoststarthttpgetwithhttpheadersmixin)
          * [`fn withPath(path)`](#fn-specinitcontainerslifecyclepoststarthttpgetwithpath)
          * [`fn withPort(port)`](#fn-specinitcontainerslifecyclepoststarthttpgetwithport)
          * [`fn withScheme(scheme)`](#fn-specinitcontainerslifecyclepoststarthttpgetwithscheme)
          * [`obj spec.initContainers.lifecycle.postStart.httpGet.httpHeaders`](#obj-specinitcontainerslifecyclepoststarthttpgethttpheaders)
            * [`fn withName(name)`](#fn-specinitcontainerslifecyclepoststarthttpgethttpheaderswithname)
            * [`fn withValue(value)`](#fn-specinitcontainerslifecyclepoststarthttpgethttpheaderswithvalue)
        * [`obj spec.initContainers.lifecycle.postStart.sleep`](#obj-specinitcontainerslifecyclepoststartsleep)
          * [`fn withSeconds(seconds)`](#fn-specinitcontainerslifecyclepoststartsleepwithseconds)
        * [`obj spec.initContainers.lifecycle.postStart.tcpSocket`](#obj-specinitcontainerslifecyclepoststarttcpsocket)
          * [`fn withHost(host)`](#fn-specinitcontainerslifecyclepoststarttcpsocketwithhost)
          * [`fn withPort(port)`](#fn-specinitcontainerslifecyclepoststarttcpsocketwithport)
      * [`obj spec.initContainers.lifecycle.preStop`](#obj-specinitcontainerslifecycleprestop)
        * [`obj spec.initContainers.lifecycle.preStop.exec`](#obj-specinitcontainerslifecycleprestopexec)
          * [`fn withCommand(command)`](#fn-specinitcontainerslifecycleprestopexecwithcommand)
          * [`fn withCommandMixin(command)`](#fn-specinitcontainerslifecycleprestopexecwithcommandmixin)
        * [`obj spec.initContainers.lifecycle.preStop.httpGet`](#obj-specinitcontainerslifecycleprestophttpget)
          * [`fn withHost(host)`](#fn-specinitcontainerslifecycleprestophttpgetwithhost)
          * [`fn withHttpHeaders(httpHeaders)`](#fn-specinitcontainerslifecycleprestophttpgetwithhttpheaders)
          * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specinitcontainerslifecycleprestophttpgetwithhttpheadersmixin)
          * [`fn withPath(path)`](#fn-specinitcontainerslifecycleprestophttpgetwithpath)
          * [`fn withPort(port)`](#fn-specinitcontainerslifecycleprestophttpgetwithport)
          * [`fn withScheme(scheme)`](#fn-specinitcontainerslifecycleprestophttpgetwithscheme)
          * [`obj spec.initContainers.lifecycle.preStop.httpGet.httpHeaders`](#obj-specinitcontainerslifecycleprestophttpgethttpheaders)
            * [`fn withName(name)`](#fn-specinitcontainerslifecycleprestophttpgethttpheaderswithname)
            * [`fn withValue(value)`](#fn-specinitcontainerslifecycleprestophttpgethttpheaderswithvalue)
        * [`obj spec.initContainers.lifecycle.preStop.sleep`](#obj-specinitcontainerslifecycleprestopsleep)
          * [`fn withSeconds(seconds)`](#fn-specinitcontainerslifecycleprestopsleepwithseconds)
        * [`obj spec.initContainers.lifecycle.preStop.tcpSocket`](#obj-specinitcontainerslifecycleprestoptcpsocket)
          * [`fn withHost(host)`](#fn-specinitcontainerslifecycleprestoptcpsocketwithhost)
          * [`fn withPort(port)`](#fn-specinitcontainerslifecycleprestoptcpsocketwithport)
    * [`obj spec.initContainers.livenessProbe`](#obj-specinitcontainerslivenessprobe)
      * [`fn withFailureThreshold(failureThreshold)`](#fn-specinitcontainerslivenessprobewithfailurethreshold)
      * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specinitcontainerslivenessprobewithinitialdelayseconds)
      * [`fn withPeriodSeconds(periodSeconds)`](#fn-specinitcontainerslivenessprobewithperiodseconds)
      * [`fn withSuccessThreshold(successThreshold)`](#fn-specinitcontainerslivenessprobewithsuccessthreshold)
      * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specinitcontainerslivenessprobewithterminationgraceperiodseconds)
      * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specinitcontainerslivenessprobewithtimeoutseconds)
      * [`obj spec.initContainers.livenessProbe.exec`](#obj-specinitcontainerslivenessprobeexec)
        * [`fn withCommand(command)`](#fn-specinitcontainerslivenessprobeexecwithcommand)
        * [`fn withCommandMixin(command)`](#fn-specinitcontainerslivenessprobeexecwithcommandmixin)
      * [`obj spec.initContainers.livenessProbe.grpc`](#obj-specinitcontainerslivenessprobegrpc)
        * [`fn withPort(port)`](#fn-specinitcontainerslivenessprobegrpcwithport)
        * [`fn withService(service)`](#fn-specinitcontainerslivenessprobegrpcwithservice)
      * [`obj spec.initContainers.livenessProbe.httpGet`](#obj-specinitcontainerslivenessprobehttpget)
        * [`fn withHost(host)`](#fn-specinitcontainerslivenessprobehttpgetwithhost)
        * [`fn withHttpHeaders(httpHeaders)`](#fn-specinitcontainerslivenessprobehttpgetwithhttpheaders)
        * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specinitcontainerslivenessprobehttpgetwithhttpheadersmixin)
        * [`fn withPath(path)`](#fn-specinitcontainerslivenessprobehttpgetwithpath)
        * [`fn withPort(port)`](#fn-specinitcontainerslivenessprobehttpgetwithport)
        * [`fn withScheme(scheme)`](#fn-specinitcontainerslivenessprobehttpgetwithscheme)
        * [`obj spec.initContainers.livenessProbe.httpGet.httpHeaders`](#obj-specinitcontainerslivenessprobehttpgethttpheaders)
          * [`fn withName(name)`](#fn-specinitcontainerslivenessprobehttpgethttpheaderswithname)
          * [`fn withValue(value)`](#fn-specinitcontainerslivenessprobehttpgethttpheaderswithvalue)
      * [`obj spec.initContainers.livenessProbe.tcpSocket`](#obj-specinitcontainerslivenessprobetcpsocket)
        * [`fn withHost(host)`](#fn-specinitcontainerslivenessprobetcpsocketwithhost)
        * [`fn withPort(port)`](#fn-specinitcontainerslivenessprobetcpsocketwithport)
    * [`obj spec.initContainers.ports`](#obj-specinitcontainersports)
      * [`fn withContainerPort(containerPort)`](#fn-specinitcontainersportswithcontainerport)
      * [`fn withHostIP(hostIP)`](#fn-specinitcontainersportswithhostip)
      * [`fn withHostPort(hostPort)`](#fn-specinitcontainersportswithhostport)
      * [`fn withName(name)`](#fn-specinitcontainersportswithname)
      * [`fn withProtocol(protocol)`](#fn-specinitcontainersportswithprotocol)
    * [`obj spec.initContainers.readinessProbe`](#obj-specinitcontainersreadinessprobe)
      * [`fn withFailureThreshold(failureThreshold)`](#fn-specinitcontainersreadinessprobewithfailurethreshold)
      * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specinitcontainersreadinessprobewithinitialdelayseconds)
      * [`fn withPeriodSeconds(periodSeconds)`](#fn-specinitcontainersreadinessprobewithperiodseconds)
      * [`fn withSuccessThreshold(successThreshold)`](#fn-specinitcontainersreadinessprobewithsuccessthreshold)
      * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specinitcontainersreadinessprobewithterminationgraceperiodseconds)
      * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specinitcontainersreadinessprobewithtimeoutseconds)
      * [`obj spec.initContainers.readinessProbe.exec`](#obj-specinitcontainersreadinessprobeexec)
        * [`fn withCommand(command)`](#fn-specinitcontainersreadinessprobeexecwithcommand)
        * [`fn withCommandMixin(command)`](#fn-specinitcontainersreadinessprobeexecwithcommandmixin)
      * [`obj spec.initContainers.readinessProbe.grpc`](#obj-specinitcontainersreadinessprobegrpc)
        * [`fn withPort(port)`](#fn-specinitcontainersreadinessprobegrpcwithport)
        * [`fn withService(service)`](#fn-specinitcontainersreadinessprobegrpcwithservice)
      * [`obj spec.initContainers.readinessProbe.httpGet`](#obj-specinitcontainersreadinessprobehttpget)
        * [`fn withHost(host)`](#fn-specinitcontainersreadinessprobehttpgetwithhost)
        * [`fn withHttpHeaders(httpHeaders)`](#fn-specinitcontainersreadinessprobehttpgetwithhttpheaders)
        * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specinitcontainersreadinessprobehttpgetwithhttpheadersmixin)
        * [`fn withPath(path)`](#fn-specinitcontainersreadinessprobehttpgetwithpath)
        * [`fn withPort(port)`](#fn-specinitcontainersreadinessprobehttpgetwithport)
        * [`fn withScheme(scheme)`](#fn-specinitcontainersreadinessprobehttpgetwithscheme)
        * [`obj spec.initContainers.readinessProbe.httpGet.httpHeaders`](#obj-specinitcontainersreadinessprobehttpgethttpheaders)
          * [`fn withName(name)`](#fn-specinitcontainersreadinessprobehttpgethttpheaderswithname)
          * [`fn withValue(value)`](#fn-specinitcontainersreadinessprobehttpgethttpheaderswithvalue)
      * [`obj spec.initContainers.readinessProbe.tcpSocket`](#obj-specinitcontainersreadinessprobetcpsocket)
        * [`fn withHost(host)`](#fn-specinitcontainersreadinessprobetcpsocketwithhost)
        * [`fn withPort(port)`](#fn-specinitcontainersreadinessprobetcpsocketwithport)
    * [`obj spec.initContainers.resizePolicy`](#obj-specinitcontainersresizepolicy)
      * [`fn withResourceName(resourceName)`](#fn-specinitcontainersresizepolicywithresourcename)
      * [`fn withRestartPolicy(restartPolicy)`](#fn-specinitcontainersresizepolicywithrestartpolicy)
    * [`obj spec.initContainers.resources`](#obj-specinitcontainersresources)
      * [`fn withClaims(claims)`](#fn-specinitcontainersresourceswithclaims)
      * [`fn withClaimsMixin(claims)`](#fn-specinitcontainersresourceswithclaimsmixin)
      * [`fn withLimits(limits)`](#fn-specinitcontainersresourceswithlimits)
      * [`fn withLimitsMixin(limits)`](#fn-specinitcontainersresourceswithlimitsmixin)
      * [`fn withRequests(requests)`](#fn-specinitcontainersresourceswithrequests)
      * [`fn withRequestsMixin(requests)`](#fn-specinitcontainersresourceswithrequestsmixin)
      * [`obj spec.initContainers.resources.claims`](#obj-specinitcontainersresourcesclaims)
        * [`fn withName(name)`](#fn-specinitcontainersresourcesclaimswithname)
    * [`obj spec.initContainers.securityContext`](#obj-specinitcontainerssecuritycontext)
      * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-specinitcontainerssecuritycontextwithallowprivilegeescalation)
      * [`fn withPrivileged(privileged)`](#fn-specinitcontainerssecuritycontextwithprivileged)
      * [`fn withProcMount(procMount)`](#fn-specinitcontainerssecuritycontextwithprocmount)
      * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-specinitcontainerssecuritycontextwithreadonlyrootfilesystem)
      * [`fn withRunAsGroup(runAsGroup)`](#fn-specinitcontainerssecuritycontextwithrunasgroup)
      * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specinitcontainerssecuritycontextwithrunasnonroot)
      * [`fn withRunAsUser(runAsUser)`](#fn-specinitcontainerssecuritycontextwithrunasuser)
      * [`obj spec.initContainers.securityContext.capabilities`](#obj-specinitcontainerssecuritycontextcapabilities)
        * [`fn withAdd(add)`](#fn-specinitcontainerssecuritycontextcapabilitieswithadd)
        * [`fn withAddMixin(add)`](#fn-specinitcontainerssecuritycontextcapabilitieswithaddmixin)
        * [`fn withDrop(drop)`](#fn-specinitcontainerssecuritycontextcapabilitieswithdrop)
        * [`fn withDropMixin(drop)`](#fn-specinitcontainerssecuritycontextcapabilitieswithdropmixin)
      * [`obj spec.initContainers.securityContext.seLinuxOptions`](#obj-specinitcontainerssecuritycontextselinuxoptions)
        * [`fn withLevel(level)`](#fn-specinitcontainerssecuritycontextselinuxoptionswithlevel)
        * [`fn withRole(role)`](#fn-specinitcontainerssecuritycontextselinuxoptionswithrole)
        * [`fn withType(type)`](#fn-specinitcontainerssecuritycontextselinuxoptionswithtype)
        * [`fn withUser(user)`](#fn-specinitcontainerssecuritycontextselinuxoptionswithuser)
      * [`obj spec.initContainers.securityContext.seccompProfile`](#obj-specinitcontainerssecuritycontextseccompprofile)
        * [`fn withLocalhostProfile(localhostProfile)`](#fn-specinitcontainerssecuritycontextseccompprofilewithlocalhostprofile)
        * [`fn withType(type)`](#fn-specinitcontainerssecuritycontextseccompprofilewithtype)
      * [`obj spec.initContainers.securityContext.windowsOptions`](#obj-specinitcontainerssecuritycontextwindowsoptions)
        * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specinitcontainerssecuritycontextwindowsoptionswithgmsacredentialspec)
        * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specinitcontainerssecuritycontextwindowsoptionswithgmsacredentialspecname)
        * [`fn withHostProcess(hostProcess)`](#fn-specinitcontainerssecuritycontextwindowsoptionswithhostprocess)
        * [`fn withRunAsUserName(runAsUserName)`](#fn-specinitcontainerssecuritycontextwindowsoptionswithrunasusername)
    * [`obj spec.initContainers.startupProbe`](#obj-specinitcontainersstartupprobe)
      * [`fn withFailureThreshold(failureThreshold)`](#fn-specinitcontainersstartupprobewithfailurethreshold)
      * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specinitcontainersstartupprobewithinitialdelayseconds)
      * [`fn withPeriodSeconds(periodSeconds)`](#fn-specinitcontainersstartupprobewithperiodseconds)
      * [`fn withSuccessThreshold(successThreshold)`](#fn-specinitcontainersstartupprobewithsuccessthreshold)
      * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specinitcontainersstartupprobewithterminationgraceperiodseconds)
      * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specinitcontainersstartupprobewithtimeoutseconds)
      * [`obj spec.initContainers.startupProbe.exec`](#obj-specinitcontainersstartupprobeexec)
        * [`fn withCommand(command)`](#fn-specinitcontainersstartupprobeexecwithcommand)
        * [`fn withCommandMixin(command)`](#fn-specinitcontainersstartupprobeexecwithcommandmixin)
      * [`obj spec.initContainers.startupProbe.grpc`](#obj-specinitcontainersstartupprobegrpc)
        * [`fn withPort(port)`](#fn-specinitcontainersstartupprobegrpcwithport)
        * [`fn withService(service)`](#fn-specinitcontainersstartupprobegrpcwithservice)
      * [`obj spec.initContainers.startupProbe.httpGet`](#obj-specinitcontainersstartupprobehttpget)
        * [`fn withHost(host)`](#fn-specinitcontainersstartupprobehttpgetwithhost)
        * [`fn withHttpHeaders(httpHeaders)`](#fn-specinitcontainersstartupprobehttpgetwithhttpheaders)
        * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specinitcontainersstartupprobehttpgetwithhttpheadersmixin)
        * [`fn withPath(path)`](#fn-specinitcontainersstartupprobehttpgetwithpath)
        * [`fn withPort(port)`](#fn-specinitcontainersstartupprobehttpgetwithport)
        * [`fn withScheme(scheme)`](#fn-specinitcontainersstartupprobehttpgetwithscheme)
        * [`obj spec.initContainers.startupProbe.httpGet.httpHeaders`](#obj-specinitcontainersstartupprobehttpgethttpheaders)
          * [`fn withName(name)`](#fn-specinitcontainersstartupprobehttpgethttpheaderswithname)
          * [`fn withValue(value)`](#fn-specinitcontainersstartupprobehttpgethttpheaderswithvalue)
      * [`obj spec.initContainers.startupProbe.tcpSocket`](#obj-specinitcontainersstartupprobetcpsocket)
        * [`fn withHost(host)`](#fn-specinitcontainersstartupprobetcpsocketwithhost)
        * [`fn withPort(port)`](#fn-specinitcontainersstartupprobetcpsocketwithport)
    * [`obj spec.initContainers.volumeDevices`](#obj-specinitcontainersvolumedevices)
      * [`fn withDevicePath(devicePath)`](#fn-specinitcontainersvolumedeviceswithdevicepath)
      * [`fn withName(name)`](#fn-specinitcontainersvolumedeviceswithname)
    * [`obj spec.initContainers.volumeMounts`](#obj-specinitcontainersvolumemounts)
      * [`fn withMountPath(mountPath)`](#fn-specinitcontainersvolumemountswithmountpath)
      * [`fn withMountPropagation(mountPropagation)`](#fn-specinitcontainersvolumemountswithmountpropagation)
      * [`fn withName(name)`](#fn-specinitcontainersvolumemountswithname)
      * [`fn withReadOnly(readOnly)`](#fn-specinitcontainersvolumemountswithreadonly)
      * [`fn withSubPath(subPath)`](#fn-specinitcontainersvolumemountswithsubpath)
      * [`fn withSubPathExpr(subPathExpr)`](#fn-specinitcontainersvolumemountswithsubpathexpr)
  * [`obj spec.kes`](#obj-speckes)
    * [`fn withAnnotations(annotations)`](#fn-speckeswithannotations)
    * [`fn withAnnotationsMixin(annotations)`](#fn-speckeswithannotationsmixin)
    * [`fn withEnv(env)`](#fn-speckeswithenv)
    * [`fn withEnvMixin(env)`](#fn-speckeswithenvmixin)
    * [`fn withGcpCredentialSecretName(gcpCredentialSecretName)`](#fn-speckeswithgcpcredentialsecretname)
    * [`fn withGcpWorkloadIdentityPool(gcpWorkloadIdentityPool)`](#fn-speckeswithgcpworkloadidentitypool)
    * [`fn withImage(image)`](#fn-speckeswithimage)
    * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-speckeswithimagepullpolicy)
    * [`fn withKeyName(keyName)`](#fn-speckeswithkeyname)
    * [`fn withLabels(labels)`](#fn-speckeswithlabels)
    * [`fn withLabelsMixin(labels)`](#fn-speckeswithlabelsmixin)
    * [`fn withNodeSelector(nodeSelector)`](#fn-speckeswithnodeselector)
    * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-speckeswithnodeselectormixin)
    * [`fn withReplicas(replicas)`](#fn-speckeswithreplicas)
    * [`fn withServiceAccountName(serviceAccountName)`](#fn-speckeswithserviceaccountname)
    * [`fn withTolerations(tolerations)`](#fn-speckeswithtolerations)
    * [`fn withTolerationsMixin(tolerations)`](#fn-speckeswithtolerationsmixin)
    * [`fn withTopologySpreadConstraints(topologySpreadConstraints)`](#fn-speckeswithtopologyspreadconstraints)
    * [`fn withTopologySpreadConstraintsMixin(topologySpreadConstraints)`](#fn-speckeswithtopologyspreadconstraintsmixin)
    * [`obj spec.kes.affinity`](#obj-speckesaffinity)
      * [`obj spec.kes.affinity.nodeAffinity`](#obj-speckesaffinitynodeaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speckesaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speckesaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speckesaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-speckesaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-speckesaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-speckesaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speckesaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
            * [`fn withMatchFields(matchFields)`](#fn-speckesaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
            * [`fn withMatchFieldsMixin(matchFields)`](#fn-speckesaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
            * [`obj spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-speckesaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
              * [`fn withKey(key)`](#fn-speckesaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-speckesaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-speckesaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-speckesaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
            * [`obj spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-speckesaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
              * [`fn withKey(key)`](#fn-speckesaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
              * [`fn withOperator(operator)`](#fn-speckesaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
              * [`fn withValues(values)`](#fn-speckesaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
              * [`fn withValuesMixin(values)`](#fn-speckesaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
        * [`obj spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speckesaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-speckesaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
          * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-speckesaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
          * [`obj spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-speckesaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-speckesaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speckesaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
            * [`fn withMatchFields(matchFields)`](#fn-speckesaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
            * [`fn withMatchFieldsMixin(matchFields)`](#fn-speckesaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
            * [`obj spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-speckesaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
              * [`fn withKey(key)`](#fn-speckesaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-speckesaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-speckesaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-speckesaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
            * [`obj spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-speckesaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
              * [`fn withKey(key)`](#fn-speckesaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
              * [`fn withOperator(operator)`](#fn-speckesaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
              * [`fn withValues(values)`](#fn-speckesaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
              * [`fn withValuesMixin(values)`](#fn-speckesaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
      * [`obj spec.kes.affinity.podAffinity`](#obj-speckesaffinitypodaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speckesaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speckesaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speckesaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speckesaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
            * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
            * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
            * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
            * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
            * [`fn withNamespaces(namespaces)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
            * [`obj spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
              * [`obj spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speckesaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
          * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
          * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
          * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
          * [`fn withNamespaces(namespaces)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
          * [`fn withNamespacesMixin(namespaces)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
          * [`fn withTopologyKey(topologyKey)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
          * [`obj spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
            * [`obj spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
              * [`fn withKey(key)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
            * [`obj spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
              * [`fn withKey(key)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-speckesaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.kes.affinity.podAntiAffinity`](#obj-speckesaffinitypodantiaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speckesaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-speckesaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speckesaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-speckesaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
            * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
            * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
            * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
            * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
            * [`fn withNamespaces(namespaces)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
            * [`obj spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
              * [`obj spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-speckesaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
          * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
          * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
          * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
          * [`fn withNamespaces(namespaces)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
          * [`fn withNamespacesMixin(namespaces)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
          * [`fn withTopologyKey(topologyKey)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
          * [`obj spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
            * [`obj spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
              * [`fn withKey(key)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
            * [`obj spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
              * [`fn withKey(key)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-speckesaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
    * [`obj spec.kes.clientCertSecret`](#obj-speckesclientcertsecret)
      * [`fn withName(name)`](#fn-speckesclientcertsecretwithname)
      * [`fn withType(type)`](#fn-speckesclientcertsecretwithtype)
    * [`obj spec.kes.containerSecurityContext`](#obj-speckescontainersecuritycontext)
      * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-speckescontainersecuritycontextwithallowprivilegeescalation)
      * [`fn withPrivileged(privileged)`](#fn-speckescontainersecuritycontextwithprivileged)
      * [`fn withProcMount(procMount)`](#fn-speckescontainersecuritycontextwithprocmount)
      * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-speckescontainersecuritycontextwithreadonlyrootfilesystem)
      * [`fn withRunAsGroup(runAsGroup)`](#fn-speckescontainersecuritycontextwithrunasgroup)
      * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-speckescontainersecuritycontextwithrunasnonroot)
      * [`fn withRunAsUser(runAsUser)`](#fn-speckescontainersecuritycontextwithrunasuser)
      * [`obj spec.kes.containerSecurityContext.capabilities`](#obj-speckescontainersecuritycontextcapabilities)
        * [`fn withAdd(add)`](#fn-speckescontainersecuritycontextcapabilitieswithadd)
        * [`fn withAddMixin(add)`](#fn-speckescontainersecuritycontextcapabilitieswithaddmixin)
        * [`fn withDrop(drop)`](#fn-speckescontainersecuritycontextcapabilitieswithdrop)
        * [`fn withDropMixin(drop)`](#fn-speckescontainersecuritycontextcapabilitieswithdropmixin)
      * [`obj spec.kes.containerSecurityContext.seLinuxOptions`](#obj-speckescontainersecuritycontextselinuxoptions)
        * [`fn withLevel(level)`](#fn-speckescontainersecuritycontextselinuxoptionswithlevel)
        * [`fn withRole(role)`](#fn-speckescontainersecuritycontextselinuxoptionswithrole)
        * [`fn withType(type)`](#fn-speckescontainersecuritycontextselinuxoptionswithtype)
        * [`fn withUser(user)`](#fn-speckescontainersecuritycontextselinuxoptionswithuser)
      * [`obj spec.kes.containerSecurityContext.seccompProfile`](#obj-speckescontainersecuritycontextseccompprofile)
        * [`fn withLocalhostProfile(localhostProfile)`](#fn-speckescontainersecuritycontextseccompprofilewithlocalhostprofile)
        * [`fn withType(type)`](#fn-speckescontainersecuritycontextseccompprofilewithtype)
      * [`obj spec.kes.containerSecurityContext.windowsOptions`](#obj-speckescontainersecuritycontextwindowsoptions)
        * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-speckescontainersecuritycontextwindowsoptionswithgmsacredentialspec)
        * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-speckescontainersecuritycontextwindowsoptionswithgmsacredentialspecname)
        * [`fn withHostProcess(hostProcess)`](#fn-speckescontainersecuritycontextwindowsoptionswithhostprocess)
        * [`fn withRunAsUserName(runAsUserName)`](#fn-speckescontainersecuritycontextwindowsoptionswithrunasusername)
    * [`obj spec.kes.env`](#obj-speckesenv)
      * [`fn withName(name)`](#fn-speckesenvwithname)
      * [`fn withValue(value)`](#fn-speckesenvwithvalue)
      * [`obj spec.kes.env.valueFrom`](#obj-speckesenvvaluefrom)
        * [`obj spec.kes.env.valueFrom.configMapKeyRef`](#obj-speckesenvvaluefromconfigmapkeyref)
          * [`fn withKey(key)`](#fn-speckesenvvaluefromconfigmapkeyrefwithkey)
          * [`fn withName(name)`](#fn-speckesenvvaluefromconfigmapkeyrefwithname)
          * [`fn withOptional(optional)`](#fn-speckesenvvaluefromconfigmapkeyrefwithoptional)
        * [`obj spec.kes.env.valueFrom.fieldRef`](#obj-speckesenvvaluefromfieldref)
          * [`fn withApiVersion(apiVersion)`](#fn-speckesenvvaluefromfieldrefwithapiversion)
          * [`fn withFieldPath(fieldPath)`](#fn-speckesenvvaluefromfieldrefwithfieldpath)
        * [`obj spec.kes.env.valueFrom.resourceFieldRef`](#obj-speckesenvvaluefromresourcefieldref)
          * [`fn withContainerName(containerName)`](#fn-speckesenvvaluefromresourcefieldrefwithcontainername)
          * [`fn withDivisor(divisor)`](#fn-speckesenvvaluefromresourcefieldrefwithdivisor)
          * [`fn withResource(resource)`](#fn-speckesenvvaluefromresourcefieldrefwithresource)
        * [`obj spec.kes.env.valueFrom.secretKeyRef`](#obj-speckesenvvaluefromsecretkeyref)
          * [`fn withKey(key)`](#fn-speckesenvvaluefromsecretkeyrefwithkey)
          * [`fn withName(name)`](#fn-speckesenvvaluefromsecretkeyrefwithname)
          * [`fn withOptional(optional)`](#fn-speckesenvvaluefromsecretkeyrefwithoptional)
    * [`obj spec.kes.externalCertSecret`](#obj-speckesexternalcertsecret)
      * [`fn withName(name)`](#fn-speckesexternalcertsecretwithname)
      * [`fn withType(type)`](#fn-speckesexternalcertsecretwithtype)
    * [`obj spec.kes.kesSecret`](#obj-speckeskessecret)
      * [`fn withName(name)`](#fn-speckeskessecretwithname)
    * [`obj spec.kes.resources`](#obj-speckesresources)
      * [`fn withClaims(claims)`](#fn-speckesresourceswithclaims)
      * [`fn withClaimsMixin(claims)`](#fn-speckesresourceswithclaimsmixin)
      * [`fn withLimits(limits)`](#fn-speckesresourceswithlimits)
      * [`fn withLimitsMixin(limits)`](#fn-speckesresourceswithlimitsmixin)
      * [`fn withRequests(requests)`](#fn-speckesresourceswithrequests)
      * [`fn withRequestsMixin(requests)`](#fn-speckesresourceswithrequestsmixin)
      * [`obj spec.kes.resources.claims`](#obj-speckesresourcesclaims)
        * [`fn withName(name)`](#fn-speckesresourcesclaimswithname)
    * [`obj spec.kes.securityContext`](#obj-speckessecuritycontext)
      * [`fn withFsGroup(fsGroup)`](#fn-speckessecuritycontextwithfsgroup)
      * [`fn withFsGroupChangePolicy(fsGroupChangePolicy)`](#fn-speckessecuritycontextwithfsgroupchangepolicy)
      * [`fn withRunAsGroup(runAsGroup)`](#fn-speckessecuritycontextwithrunasgroup)
      * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-speckessecuritycontextwithrunasnonroot)
      * [`fn withRunAsUser(runAsUser)`](#fn-speckessecuritycontextwithrunasuser)
      * [`fn withSupplementalGroups(supplementalGroups)`](#fn-speckessecuritycontextwithsupplementalgroups)
      * [`fn withSupplementalGroupsMixin(supplementalGroups)`](#fn-speckessecuritycontextwithsupplementalgroupsmixin)
      * [`fn withSysctls(sysctls)`](#fn-speckessecuritycontextwithsysctls)
      * [`fn withSysctlsMixin(sysctls)`](#fn-speckessecuritycontextwithsysctlsmixin)
      * [`obj spec.kes.securityContext.seLinuxOptions`](#obj-speckessecuritycontextselinuxoptions)
        * [`fn withLevel(level)`](#fn-speckessecuritycontextselinuxoptionswithlevel)
        * [`fn withRole(role)`](#fn-speckessecuritycontextselinuxoptionswithrole)
        * [`fn withType(type)`](#fn-speckessecuritycontextselinuxoptionswithtype)
        * [`fn withUser(user)`](#fn-speckessecuritycontextselinuxoptionswithuser)
      * [`obj spec.kes.securityContext.seccompProfile`](#obj-speckessecuritycontextseccompprofile)
        * [`fn withLocalhostProfile(localhostProfile)`](#fn-speckessecuritycontextseccompprofilewithlocalhostprofile)
        * [`fn withType(type)`](#fn-speckessecuritycontextseccompprofilewithtype)
      * [`obj spec.kes.securityContext.sysctls`](#obj-speckessecuritycontextsysctls)
        * [`fn withName(name)`](#fn-speckessecuritycontextsysctlswithname)
        * [`fn withValue(value)`](#fn-speckessecuritycontextsysctlswithvalue)
      * [`obj spec.kes.securityContext.windowsOptions`](#obj-speckessecuritycontextwindowsoptions)
        * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-speckessecuritycontextwindowsoptionswithgmsacredentialspec)
        * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-speckessecuritycontextwindowsoptionswithgmsacredentialspecname)
        * [`fn withHostProcess(hostProcess)`](#fn-speckessecuritycontextwindowsoptionswithhostprocess)
        * [`fn withRunAsUserName(runAsUserName)`](#fn-speckessecuritycontextwindowsoptionswithrunasusername)
    * [`obj spec.kes.tolerations`](#obj-speckestolerations)
      * [`fn withEffect(effect)`](#fn-speckestolerationswitheffect)
      * [`fn withKey(key)`](#fn-speckestolerationswithkey)
      * [`fn withOperator(operator)`](#fn-speckestolerationswithoperator)
      * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-speckestolerationswithtolerationseconds)
      * [`fn withValue(value)`](#fn-speckestolerationswithvalue)
    * [`obj spec.kes.topologySpreadConstraints`](#obj-speckestopologyspreadconstraints)
      * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-speckestopologyspreadconstraintswithmatchlabelkeys)
      * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-speckestopologyspreadconstraintswithmatchlabelkeysmixin)
      * [`fn withMaxSkew(maxSkew)`](#fn-speckestopologyspreadconstraintswithmaxskew)
      * [`fn withMinDomains(minDomains)`](#fn-speckestopologyspreadconstraintswithmindomains)
      * [`fn withNodeAffinityPolicy(nodeAffinityPolicy)`](#fn-speckestopologyspreadconstraintswithnodeaffinitypolicy)
      * [`fn withNodeTaintsPolicy(nodeTaintsPolicy)`](#fn-speckestopologyspreadconstraintswithnodetaintspolicy)
      * [`fn withTopologyKey(topologyKey)`](#fn-speckestopologyspreadconstraintswithtopologykey)
      * [`fn withWhenUnsatisfiable(whenUnsatisfiable)`](#fn-speckestopologyspreadconstraintswithwhenunsatisfiable)
      * [`obj spec.kes.topologySpreadConstraints.labelSelector`](#obj-speckestopologyspreadconstraintslabelselector)
        * [`fn withMatchExpressions(matchExpressions)`](#fn-speckestopologyspreadconstraintslabelselectorwithmatchexpressions)
        * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-speckestopologyspreadconstraintslabelselectorwithmatchexpressionsmixin)
        * [`fn withMatchLabels(matchLabels)`](#fn-speckestopologyspreadconstraintslabelselectorwithmatchlabels)
        * [`fn withMatchLabelsMixin(matchLabels)`](#fn-speckestopologyspreadconstraintslabelselectorwithmatchlabelsmixin)
        * [`obj spec.kes.topologySpreadConstraints.labelSelector.matchExpressions`](#obj-speckestopologyspreadconstraintslabelselectormatchexpressions)
          * [`fn withKey(key)`](#fn-speckestopologyspreadconstraintslabelselectormatchexpressionswithkey)
          * [`fn withOperator(operator)`](#fn-speckestopologyspreadconstraintslabelselectormatchexpressionswithoperator)
          * [`fn withValues(values)`](#fn-speckestopologyspreadconstraintslabelselectormatchexpressionswithvalues)
          * [`fn withValuesMixin(values)`](#fn-speckestopologyspreadconstraintslabelselectormatchexpressionswithvaluesmixin)
  * [`obj spec.lifecycle`](#obj-speclifecycle)
    * [`obj spec.lifecycle.postStart`](#obj-speclifecyclepoststart)
      * [`obj spec.lifecycle.postStart.exec`](#obj-speclifecyclepoststartexec)
        * [`fn withCommand(command)`](#fn-speclifecyclepoststartexecwithcommand)
        * [`fn withCommandMixin(command)`](#fn-speclifecyclepoststartexecwithcommandmixin)
      * [`obj spec.lifecycle.postStart.httpGet`](#obj-speclifecyclepoststarthttpget)
        * [`fn withHost(host)`](#fn-speclifecyclepoststarthttpgetwithhost)
        * [`fn withHttpHeaders(httpHeaders)`](#fn-speclifecyclepoststarthttpgetwithhttpheaders)
        * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-speclifecyclepoststarthttpgetwithhttpheadersmixin)
        * [`fn withPath(path)`](#fn-speclifecyclepoststarthttpgetwithpath)
        * [`fn withPort(port)`](#fn-speclifecyclepoststarthttpgetwithport)
        * [`fn withScheme(scheme)`](#fn-speclifecyclepoststarthttpgetwithscheme)
        * [`obj spec.lifecycle.postStart.httpGet.httpHeaders`](#obj-speclifecyclepoststarthttpgethttpheaders)
          * [`fn withName(name)`](#fn-speclifecyclepoststarthttpgethttpheaderswithname)
          * [`fn withValue(value)`](#fn-speclifecyclepoststarthttpgethttpheaderswithvalue)
      * [`obj spec.lifecycle.postStart.tcpSocket`](#obj-speclifecyclepoststarttcpsocket)
        * [`fn withHost(host)`](#fn-speclifecyclepoststarttcpsocketwithhost)
        * [`fn withPort(port)`](#fn-speclifecyclepoststarttcpsocketwithport)
    * [`obj spec.lifecycle.preStop`](#obj-speclifecycleprestop)
      * [`obj spec.lifecycle.preStop.exec`](#obj-speclifecycleprestopexec)
        * [`fn withCommand(command)`](#fn-speclifecycleprestopexecwithcommand)
        * [`fn withCommandMixin(command)`](#fn-speclifecycleprestopexecwithcommandmixin)
      * [`obj spec.lifecycle.preStop.httpGet`](#obj-speclifecycleprestophttpget)
        * [`fn withHost(host)`](#fn-speclifecycleprestophttpgetwithhost)
        * [`fn withHttpHeaders(httpHeaders)`](#fn-speclifecycleprestophttpgetwithhttpheaders)
        * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-speclifecycleprestophttpgetwithhttpheadersmixin)
        * [`fn withPath(path)`](#fn-speclifecycleprestophttpgetwithpath)
        * [`fn withPort(port)`](#fn-speclifecycleprestophttpgetwithport)
        * [`fn withScheme(scheme)`](#fn-speclifecycleprestophttpgetwithscheme)
        * [`obj spec.lifecycle.preStop.httpGet.httpHeaders`](#obj-speclifecycleprestophttpgethttpheaders)
          * [`fn withName(name)`](#fn-speclifecycleprestophttpgethttpheaderswithname)
          * [`fn withValue(value)`](#fn-speclifecycleprestophttpgethttpheaderswithvalue)
      * [`obj spec.lifecycle.preStop.tcpSocket`](#obj-speclifecycleprestoptcpsocket)
        * [`fn withHost(host)`](#fn-speclifecycleprestoptcpsocketwithhost)
        * [`fn withPort(port)`](#fn-speclifecycleprestoptcpsocketwithport)
  * [`obj spec.liveness`](#obj-specliveness)
    * [`fn withFailureThreshold(failureThreshold)`](#fn-speclivenesswithfailurethreshold)
    * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-speclivenesswithinitialdelayseconds)
    * [`fn withPeriodSeconds(periodSeconds)`](#fn-speclivenesswithperiodseconds)
    * [`fn withSuccessThreshold(successThreshold)`](#fn-speclivenesswithsuccessthreshold)
    * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-speclivenesswithterminationgraceperiodseconds)
    * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-speclivenesswithtimeoutseconds)
    * [`obj spec.liveness.exec`](#obj-speclivenessexec)
      * [`fn withCommand(command)`](#fn-speclivenessexecwithcommand)
      * [`fn withCommandMixin(command)`](#fn-speclivenessexecwithcommandmixin)
    * [`obj spec.liveness.grpc`](#obj-speclivenessgrpc)
      * [`fn withPort(port)`](#fn-speclivenessgrpcwithport)
      * [`fn withService(service)`](#fn-speclivenessgrpcwithservice)
    * [`obj spec.liveness.httpGet`](#obj-speclivenesshttpget)
      * [`fn withHost(host)`](#fn-speclivenesshttpgetwithhost)
      * [`fn withHttpHeaders(httpHeaders)`](#fn-speclivenesshttpgetwithhttpheaders)
      * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-speclivenesshttpgetwithhttpheadersmixin)
      * [`fn withPath(path)`](#fn-speclivenesshttpgetwithpath)
      * [`fn withPort(port)`](#fn-speclivenesshttpgetwithport)
      * [`fn withScheme(scheme)`](#fn-speclivenesshttpgetwithscheme)
      * [`obj spec.liveness.httpGet.httpHeaders`](#obj-speclivenesshttpgethttpheaders)
        * [`fn withName(name)`](#fn-speclivenesshttpgethttpheaderswithname)
        * [`fn withValue(value)`](#fn-speclivenesshttpgethttpheaderswithvalue)
    * [`obj spec.liveness.tcpSocket`](#obj-speclivenesstcpsocket)
      * [`fn withHost(host)`](#fn-speclivenesstcpsocketwithhost)
      * [`fn withPort(port)`](#fn-speclivenesstcpsocketwithport)
  * [`obj spec.logging`](#obj-speclogging)
    * [`fn withAnonymous(anonymous)`](#fn-specloggingwithanonymous)
    * [`fn withJson(json)`](#fn-specloggingwithjson)
    * [`fn withQuiet(quiet)`](#fn-specloggingwithquiet)
  * [`obj spec.pools`](#obj-specpools)
    * [`fn withAnnotations(annotations)`](#fn-specpoolswithannotations)
    * [`fn withAnnotationsMixin(annotations)`](#fn-specpoolswithannotationsmixin)
    * [`fn withLabels(labels)`](#fn-specpoolswithlabels)
    * [`fn withLabelsMixin(labels)`](#fn-specpoolswithlabelsmixin)
    * [`fn withName(name)`](#fn-specpoolswithname)
    * [`fn withNodeSelector(nodeSelector)`](#fn-specpoolswithnodeselector)
    * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-specpoolswithnodeselectormixin)
    * [`fn withReclaimStorage(reclaimStorage)`](#fn-specpoolswithreclaimstorage)
    * [`fn withRuntimeClassName(runtimeClassName)`](#fn-specpoolswithruntimeclassname)
    * [`fn withServers(servers)`](#fn-specpoolswithservers)
    * [`fn withTolerations(tolerations)`](#fn-specpoolswithtolerations)
    * [`fn withTolerationsMixin(tolerations)`](#fn-specpoolswithtolerationsmixin)
    * [`fn withTopologySpreadConstraints(topologySpreadConstraints)`](#fn-specpoolswithtopologyspreadconstraints)
    * [`fn withTopologySpreadConstraintsMixin(topologySpreadConstraints)`](#fn-specpoolswithtopologyspreadconstraintsmixin)
    * [`fn withVolumesPerServer(volumesPerServer)`](#fn-specpoolswithvolumesperserver)
    * [`obj spec.pools.affinity`](#obj-specpoolsaffinity)
      * [`obj spec.pools.affinity.nodeAffinity`](#obj-specpoolsaffinitynodeaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specpoolsaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specpoolsaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specpoolsaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-specpoolsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-specpoolsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specpoolsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpoolsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
            * [`fn withMatchFields(matchFields)`](#fn-specpoolsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
            * [`fn withMatchFieldsMixin(matchFields)`](#fn-specpoolsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
            * [`obj spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-specpoolsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
              * [`fn withKey(key)`](#fn-specpoolsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specpoolsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specpoolsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specpoolsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
            * [`obj spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-specpoolsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
              * [`fn withKey(key)`](#fn-specpoolsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
              * [`fn withOperator(operator)`](#fn-specpoolsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
              * [`fn withValues(values)`](#fn-specpoolsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specpoolsaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
        * [`obj spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specpoolsaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-specpoolsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
          * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-specpoolsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
          * [`obj spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-specpoolsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specpoolsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpoolsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
            * [`fn withMatchFields(matchFields)`](#fn-specpoolsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
            * [`fn withMatchFieldsMixin(matchFields)`](#fn-specpoolsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
            * [`obj spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-specpoolsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
              * [`fn withKey(key)`](#fn-specpoolsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specpoolsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specpoolsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specpoolsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
            * [`obj spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-specpoolsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
              * [`fn withKey(key)`](#fn-specpoolsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
              * [`fn withOperator(operator)`](#fn-specpoolsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
              * [`fn withValues(values)`](#fn-specpoolsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specpoolsaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
      * [`obj spec.pools.affinity.podAffinity`](#obj-specpoolsaffinitypodaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specpoolsaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specpoolsaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specpoolsaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specpoolsaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
            * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
            * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
            * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
            * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
            * [`fn withNamespaces(namespaces)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
            * [`obj spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
              * [`obj spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specpoolsaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
          * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
          * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
          * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
          * [`fn withNamespaces(namespaces)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
          * [`fn withNamespacesMixin(namespaces)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
          * [`fn withTopologyKey(topologyKey)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
          * [`obj spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
            * [`obj spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
            * [`obj spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specpoolsaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.pools.affinity.podAntiAffinity`](#obj-specpoolsaffinitypodantiaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specpoolsaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specpoolsaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specpoolsaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specpoolsaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
            * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
            * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
            * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
            * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
            * [`fn withNamespaces(namespaces)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
            * [`obj spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
              * [`obj spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specpoolsaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
          * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
          * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
          * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
          * [`fn withNamespaces(namespaces)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
          * [`fn withNamespacesMixin(namespaces)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
          * [`fn withTopologyKey(topologyKey)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
          * [`obj spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
            * [`obj spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
            * [`obj spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specpoolsaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
    * [`obj spec.pools.containerSecurityContext`](#obj-specpoolscontainersecuritycontext)
      * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-specpoolscontainersecuritycontextwithallowprivilegeescalation)
      * [`fn withPrivileged(privileged)`](#fn-specpoolscontainersecuritycontextwithprivileged)
      * [`fn withProcMount(procMount)`](#fn-specpoolscontainersecuritycontextwithprocmount)
      * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-specpoolscontainersecuritycontextwithreadonlyrootfilesystem)
      * [`fn withRunAsGroup(runAsGroup)`](#fn-specpoolscontainersecuritycontextwithrunasgroup)
      * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specpoolscontainersecuritycontextwithrunasnonroot)
      * [`fn withRunAsUser(runAsUser)`](#fn-specpoolscontainersecuritycontextwithrunasuser)
      * [`obj spec.pools.containerSecurityContext.capabilities`](#obj-specpoolscontainersecuritycontextcapabilities)
        * [`fn withAdd(add)`](#fn-specpoolscontainersecuritycontextcapabilitieswithadd)
        * [`fn withAddMixin(add)`](#fn-specpoolscontainersecuritycontextcapabilitieswithaddmixin)
        * [`fn withDrop(drop)`](#fn-specpoolscontainersecuritycontextcapabilitieswithdrop)
        * [`fn withDropMixin(drop)`](#fn-specpoolscontainersecuritycontextcapabilitieswithdropmixin)
      * [`obj spec.pools.containerSecurityContext.seLinuxOptions`](#obj-specpoolscontainersecuritycontextselinuxoptions)
        * [`fn withLevel(level)`](#fn-specpoolscontainersecuritycontextselinuxoptionswithlevel)
        * [`fn withRole(role)`](#fn-specpoolscontainersecuritycontextselinuxoptionswithrole)
        * [`fn withType(type)`](#fn-specpoolscontainersecuritycontextselinuxoptionswithtype)
        * [`fn withUser(user)`](#fn-specpoolscontainersecuritycontextselinuxoptionswithuser)
      * [`obj spec.pools.containerSecurityContext.seccompProfile`](#obj-specpoolscontainersecuritycontextseccompprofile)
        * [`fn withLocalhostProfile(localhostProfile)`](#fn-specpoolscontainersecuritycontextseccompprofilewithlocalhostprofile)
        * [`fn withType(type)`](#fn-specpoolscontainersecuritycontextseccompprofilewithtype)
      * [`obj spec.pools.containerSecurityContext.windowsOptions`](#obj-specpoolscontainersecuritycontextwindowsoptions)
        * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specpoolscontainersecuritycontextwindowsoptionswithgmsacredentialspec)
        * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specpoolscontainersecuritycontextwindowsoptionswithgmsacredentialspecname)
        * [`fn withHostProcess(hostProcess)`](#fn-specpoolscontainersecuritycontextwindowsoptionswithhostprocess)
        * [`fn withRunAsUserName(runAsUserName)`](#fn-specpoolscontainersecuritycontextwindowsoptionswithrunasusername)
    * [`obj spec.pools.resources`](#obj-specpoolsresources)
      * [`fn withClaims(claims)`](#fn-specpoolsresourceswithclaims)
      * [`fn withClaimsMixin(claims)`](#fn-specpoolsresourceswithclaimsmixin)
      * [`fn withLimits(limits)`](#fn-specpoolsresourceswithlimits)
      * [`fn withLimitsMixin(limits)`](#fn-specpoolsresourceswithlimitsmixin)
      * [`fn withRequests(requests)`](#fn-specpoolsresourceswithrequests)
      * [`fn withRequestsMixin(requests)`](#fn-specpoolsresourceswithrequestsmixin)
      * [`obj spec.pools.resources.claims`](#obj-specpoolsresourcesclaims)
        * [`fn withName(name)`](#fn-specpoolsresourcesclaimswithname)
    * [`obj spec.pools.securityContext`](#obj-specpoolssecuritycontext)
      * [`fn withFsGroup(fsGroup)`](#fn-specpoolssecuritycontextwithfsgroup)
      * [`fn withFsGroupChangePolicy(fsGroupChangePolicy)`](#fn-specpoolssecuritycontextwithfsgroupchangepolicy)
      * [`fn withRunAsGroup(runAsGroup)`](#fn-specpoolssecuritycontextwithrunasgroup)
      * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specpoolssecuritycontextwithrunasnonroot)
      * [`fn withRunAsUser(runAsUser)`](#fn-specpoolssecuritycontextwithrunasuser)
      * [`fn withSupplementalGroups(supplementalGroups)`](#fn-specpoolssecuritycontextwithsupplementalgroups)
      * [`fn withSupplementalGroupsMixin(supplementalGroups)`](#fn-specpoolssecuritycontextwithsupplementalgroupsmixin)
      * [`fn withSysctls(sysctls)`](#fn-specpoolssecuritycontextwithsysctls)
      * [`fn withSysctlsMixin(sysctls)`](#fn-specpoolssecuritycontextwithsysctlsmixin)
      * [`obj spec.pools.securityContext.seLinuxOptions`](#obj-specpoolssecuritycontextselinuxoptions)
        * [`fn withLevel(level)`](#fn-specpoolssecuritycontextselinuxoptionswithlevel)
        * [`fn withRole(role)`](#fn-specpoolssecuritycontextselinuxoptionswithrole)
        * [`fn withType(type)`](#fn-specpoolssecuritycontextselinuxoptionswithtype)
        * [`fn withUser(user)`](#fn-specpoolssecuritycontextselinuxoptionswithuser)
      * [`obj spec.pools.securityContext.seccompProfile`](#obj-specpoolssecuritycontextseccompprofile)
        * [`fn withLocalhostProfile(localhostProfile)`](#fn-specpoolssecuritycontextseccompprofilewithlocalhostprofile)
        * [`fn withType(type)`](#fn-specpoolssecuritycontextseccompprofilewithtype)
      * [`obj spec.pools.securityContext.sysctls`](#obj-specpoolssecuritycontextsysctls)
        * [`fn withName(name)`](#fn-specpoolssecuritycontextsysctlswithname)
        * [`fn withValue(value)`](#fn-specpoolssecuritycontextsysctlswithvalue)
      * [`obj spec.pools.securityContext.windowsOptions`](#obj-specpoolssecuritycontextwindowsoptions)
        * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specpoolssecuritycontextwindowsoptionswithgmsacredentialspec)
        * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specpoolssecuritycontextwindowsoptionswithgmsacredentialspecname)
        * [`fn withHostProcess(hostProcess)`](#fn-specpoolssecuritycontextwindowsoptionswithhostprocess)
        * [`fn withRunAsUserName(runAsUserName)`](#fn-specpoolssecuritycontextwindowsoptionswithrunasusername)
    * [`obj spec.pools.tolerations`](#obj-specpoolstolerations)
      * [`fn withEffect(effect)`](#fn-specpoolstolerationswitheffect)
      * [`fn withKey(key)`](#fn-specpoolstolerationswithkey)
      * [`fn withOperator(operator)`](#fn-specpoolstolerationswithoperator)
      * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-specpoolstolerationswithtolerationseconds)
      * [`fn withValue(value)`](#fn-specpoolstolerationswithvalue)
    * [`obj spec.pools.topologySpreadConstraints`](#obj-specpoolstopologyspreadconstraints)
      * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specpoolstopologyspreadconstraintswithmatchlabelkeys)
      * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specpoolstopologyspreadconstraintswithmatchlabelkeysmixin)
      * [`fn withMaxSkew(maxSkew)`](#fn-specpoolstopologyspreadconstraintswithmaxskew)
      * [`fn withMinDomains(minDomains)`](#fn-specpoolstopologyspreadconstraintswithmindomains)
      * [`fn withNodeAffinityPolicy(nodeAffinityPolicy)`](#fn-specpoolstopologyspreadconstraintswithnodeaffinitypolicy)
      * [`fn withNodeTaintsPolicy(nodeTaintsPolicy)`](#fn-specpoolstopologyspreadconstraintswithnodetaintspolicy)
      * [`fn withTopologyKey(topologyKey)`](#fn-specpoolstopologyspreadconstraintswithtopologykey)
      * [`fn withWhenUnsatisfiable(whenUnsatisfiable)`](#fn-specpoolstopologyspreadconstraintswithwhenunsatisfiable)
      * [`obj spec.pools.topologySpreadConstraints.labelSelector`](#obj-specpoolstopologyspreadconstraintslabelselector)
        * [`fn withMatchExpressions(matchExpressions)`](#fn-specpoolstopologyspreadconstraintslabelselectorwithmatchexpressions)
        * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpoolstopologyspreadconstraintslabelselectorwithmatchexpressionsmixin)
        * [`fn withMatchLabels(matchLabels)`](#fn-specpoolstopologyspreadconstraintslabelselectorwithmatchlabels)
        * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpoolstopologyspreadconstraintslabelselectorwithmatchlabelsmixin)
        * [`obj spec.pools.topologySpreadConstraints.labelSelector.matchExpressions`](#obj-specpoolstopologyspreadconstraintslabelselectormatchexpressions)
          * [`fn withKey(key)`](#fn-specpoolstopologyspreadconstraintslabelselectormatchexpressionswithkey)
          * [`fn withOperator(operator)`](#fn-specpoolstopologyspreadconstraintslabelselectormatchexpressionswithoperator)
          * [`fn withValues(values)`](#fn-specpoolstopologyspreadconstraintslabelselectormatchexpressionswithvalues)
          * [`fn withValuesMixin(values)`](#fn-specpoolstopologyspreadconstraintslabelselectormatchexpressionswithvaluesmixin)
    * [`obj spec.pools.volumeClaimTemplate`](#obj-specpoolsvolumeclaimtemplate)
      * [`fn withApiVersion(apiVersion)`](#fn-specpoolsvolumeclaimtemplatewithapiversion)
      * [`fn withKind(kind)`](#fn-specpoolsvolumeclaimtemplatewithkind)
      * [`obj spec.pools.volumeClaimTemplate.metadata`](#obj-specpoolsvolumeclaimtemplatemetadata)
        * [`fn withAnnotations(annotations)`](#fn-specpoolsvolumeclaimtemplatemetadatawithannotations)
        * [`fn withAnnotationsMixin(annotations)`](#fn-specpoolsvolumeclaimtemplatemetadatawithannotationsmixin)
        * [`fn withFinalizers(finalizers)`](#fn-specpoolsvolumeclaimtemplatemetadatawithfinalizers)
        * [`fn withFinalizersMixin(finalizers)`](#fn-specpoolsvolumeclaimtemplatemetadatawithfinalizersmixin)
        * [`fn withLabels(labels)`](#fn-specpoolsvolumeclaimtemplatemetadatawithlabels)
        * [`fn withLabelsMixin(labels)`](#fn-specpoolsvolumeclaimtemplatemetadatawithlabelsmixin)
        * [`fn withName(name)`](#fn-specpoolsvolumeclaimtemplatemetadatawithname)
        * [`fn withNamespace(namespace)`](#fn-specpoolsvolumeclaimtemplatemetadatawithnamespace)
      * [`obj spec.pools.volumeClaimTemplate.spec`](#obj-specpoolsvolumeclaimtemplatespec)
        * [`fn withAccessModes(accessModes)`](#fn-specpoolsvolumeclaimtemplatespecwithaccessmodes)
        * [`fn withAccessModesMixin(accessModes)`](#fn-specpoolsvolumeclaimtemplatespecwithaccessmodesmixin)
        * [`fn withStorageClassName(storageClassName)`](#fn-specpoolsvolumeclaimtemplatespecwithstorageclassname)
        * [`fn withVolumeAttributesClassName(volumeAttributesClassName)`](#fn-specpoolsvolumeclaimtemplatespecwithvolumeattributesclassname)
        * [`fn withVolumeMode(volumeMode)`](#fn-specpoolsvolumeclaimtemplatespecwithvolumemode)
        * [`fn withVolumeName(volumeName)`](#fn-specpoolsvolumeclaimtemplatespecwithvolumename)
        * [`obj spec.pools.volumeClaimTemplate.spec.dataSource`](#obj-specpoolsvolumeclaimtemplatespecdatasource)
          * [`fn withApiGroup(apiGroup)`](#fn-specpoolsvolumeclaimtemplatespecdatasourcewithapigroup)
          * [`fn withKind(kind)`](#fn-specpoolsvolumeclaimtemplatespecdatasourcewithkind)
          * [`fn withName(name)`](#fn-specpoolsvolumeclaimtemplatespecdatasourcewithname)
        * [`obj spec.pools.volumeClaimTemplate.spec.dataSourceRef`](#obj-specpoolsvolumeclaimtemplatespecdatasourceref)
          * [`fn withApiGroup(apiGroup)`](#fn-specpoolsvolumeclaimtemplatespecdatasourcerefwithapigroup)
          * [`fn withKind(kind)`](#fn-specpoolsvolumeclaimtemplatespecdatasourcerefwithkind)
          * [`fn withName(name)`](#fn-specpoolsvolumeclaimtemplatespecdatasourcerefwithname)
          * [`fn withNamespace(namespace)`](#fn-specpoolsvolumeclaimtemplatespecdatasourcerefwithnamespace)
        * [`obj spec.pools.volumeClaimTemplate.spec.resources`](#obj-specpoolsvolumeclaimtemplatespecresources)
          * [`fn withLimits(limits)`](#fn-specpoolsvolumeclaimtemplatespecresourceswithlimits)
          * [`fn withLimitsMixin(limits)`](#fn-specpoolsvolumeclaimtemplatespecresourceswithlimitsmixin)
          * [`fn withRequests(requests)`](#fn-specpoolsvolumeclaimtemplatespecresourceswithrequests)
          * [`fn withRequestsMixin(requests)`](#fn-specpoolsvolumeclaimtemplatespecresourceswithrequestsmixin)
        * [`obj spec.pools.volumeClaimTemplate.spec.selector`](#obj-specpoolsvolumeclaimtemplatespecselector)
          * [`fn withMatchExpressions(matchExpressions)`](#fn-specpoolsvolumeclaimtemplatespecselectorwithmatchexpressions)
          * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpoolsvolumeclaimtemplatespecselectorwithmatchexpressionsmixin)
          * [`fn withMatchLabels(matchLabels)`](#fn-specpoolsvolumeclaimtemplatespecselectorwithmatchlabels)
          * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpoolsvolumeclaimtemplatespecselectorwithmatchlabelsmixin)
          * [`obj spec.pools.volumeClaimTemplate.spec.selector.matchExpressions`](#obj-specpoolsvolumeclaimtemplatespecselectormatchexpressions)
            * [`fn withKey(key)`](#fn-specpoolsvolumeclaimtemplatespecselectormatchexpressionswithkey)
            * [`fn withOperator(operator)`](#fn-specpoolsvolumeclaimtemplatespecselectormatchexpressionswithoperator)
            * [`fn withValues(values)`](#fn-specpoolsvolumeclaimtemplatespecselectormatchexpressionswithvalues)
            * [`fn withValuesMixin(values)`](#fn-specpoolsvolumeclaimtemplatespecselectormatchexpressionswithvaluesmixin)
  * [`obj spec.readiness`](#obj-specreadiness)
    * [`fn withFailureThreshold(failureThreshold)`](#fn-specreadinesswithfailurethreshold)
    * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specreadinesswithinitialdelayseconds)
    * [`fn withPeriodSeconds(periodSeconds)`](#fn-specreadinesswithperiodseconds)
    * [`fn withSuccessThreshold(successThreshold)`](#fn-specreadinesswithsuccessthreshold)
    * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specreadinesswithterminationgraceperiodseconds)
    * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specreadinesswithtimeoutseconds)
    * [`obj spec.readiness.exec`](#obj-specreadinessexec)
      * [`fn withCommand(command)`](#fn-specreadinessexecwithcommand)
      * [`fn withCommandMixin(command)`](#fn-specreadinessexecwithcommandmixin)
    * [`obj spec.readiness.grpc`](#obj-specreadinessgrpc)
      * [`fn withPort(port)`](#fn-specreadinessgrpcwithport)
      * [`fn withService(service)`](#fn-specreadinessgrpcwithservice)
    * [`obj spec.readiness.httpGet`](#obj-specreadinesshttpget)
      * [`fn withHost(host)`](#fn-specreadinesshttpgetwithhost)
      * [`fn withHttpHeaders(httpHeaders)`](#fn-specreadinesshttpgetwithhttpheaders)
      * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specreadinesshttpgetwithhttpheadersmixin)
      * [`fn withPath(path)`](#fn-specreadinesshttpgetwithpath)
      * [`fn withPort(port)`](#fn-specreadinesshttpgetwithport)
      * [`fn withScheme(scheme)`](#fn-specreadinesshttpgetwithscheme)
      * [`obj spec.readiness.httpGet.httpHeaders`](#obj-specreadinesshttpgethttpheaders)
        * [`fn withName(name)`](#fn-specreadinesshttpgethttpheaderswithname)
        * [`fn withValue(value)`](#fn-specreadinesshttpgethttpheaderswithvalue)
    * [`obj spec.readiness.tcpSocket`](#obj-specreadinesstcpsocket)
      * [`fn withHost(host)`](#fn-specreadinesstcpsocketwithhost)
      * [`fn withPort(port)`](#fn-specreadinesstcpsocketwithport)
  * [`obj spec.serviceMetadata`](#obj-specservicemetadata)
    * [`fn withConsoleServiceAnnotations(consoleServiceAnnotations)`](#fn-specservicemetadatawithconsoleserviceannotations)
    * [`fn withConsoleServiceAnnotationsMixin(consoleServiceAnnotations)`](#fn-specservicemetadatawithconsoleserviceannotationsmixin)
    * [`fn withConsoleServiceLabels(consoleServiceLabels)`](#fn-specservicemetadatawithconsoleservicelabels)
    * [`fn withConsoleServiceLabelsMixin(consoleServiceLabels)`](#fn-specservicemetadatawithconsoleservicelabelsmixin)
    * [`fn withMinioServiceAnnotations(minioServiceAnnotations)`](#fn-specservicemetadatawithminioserviceannotations)
    * [`fn withMinioServiceAnnotationsMixin(minioServiceAnnotations)`](#fn-specservicemetadatawithminioserviceannotationsmixin)
    * [`fn withMinioServiceLabels(minioServiceLabels)`](#fn-specservicemetadatawithminioservicelabels)
    * [`fn withMinioServiceLabelsMixin(minioServiceLabels)`](#fn-specservicemetadatawithminioservicelabelsmixin)
  * [`obj spec.sideCars`](#obj-specsidecars)
    * [`fn withContainers(containers)`](#fn-specsidecarswithcontainers)
    * [`fn withContainersMixin(containers)`](#fn-specsidecarswithcontainersmixin)
    * [`fn withVolumeClaimTemplates(volumeClaimTemplates)`](#fn-specsidecarswithvolumeclaimtemplates)
    * [`fn withVolumeClaimTemplatesMixin(volumeClaimTemplates)`](#fn-specsidecarswithvolumeclaimtemplatesmixin)
    * [`fn withVolumes(volumes)`](#fn-specsidecarswithvolumes)
    * [`fn withVolumesMixin(volumes)`](#fn-specsidecarswithvolumesmixin)
    * [`obj spec.sideCars.containers`](#obj-specsidecarscontainers)
      * [`fn withArgs(args)`](#fn-specsidecarscontainerswithargs)
      * [`fn withArgsMixin(args)`](#fn-specsidecarscontainerswithargsmixin)
      * [`fn withCommand(command)`](#fn-specsidecarscontainerswithcommand)
      * [`fn withCommandMixin(command)`](#fn-specsidecarscontainerswithcommandmixin)
      * [`fn withEnv(env)`](#fn-specsidecarscontainerswithenv)
      * [`fn withEnvFrom(envFrom)`](#fn-specsidecarscontainerswithenvfrom)
      * [`fn withEnvFromMixin(envFrom)`](#fn-specsidecarscontainerswithenvfrommixin)
      * [`fn withEnvMixin(env)`](#fn-specsidecarscontainerswithenvmixin)
      * [`fn withImage(image)`](#fn-specsidecarscontainerswithimage)
      * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-specsidecarscontainerswithimagepullpolicy)
      * [`fn withName(name)`](#fn-specsidecarscontainerswithname)
      * [`fn withPorts(ports)`](#fn-specsidecarscontainerswithports)
      * [`fn withPortsMixin(ports)`](#fn-specsidecarscontainerswithportsmixin)
      * [`fn withResizePolicy(resizePolicy)`](#fn-specsidecarscontainerswithresizepolicy)
      * [`fn withResizePolicyMixin(resizePolicy)`](#fn-specsidecarscontainerswithresizepolicymixin)
      * [`fn withRestartPolicy(restartPolicy)`](#fn-specsidecarscontainerswithrestartpolicy)
      * [`fn withStdin(stdin)`](#fn-specsidecarscontainerswithstdin)
      * [`fn withStdinOnce(stdinOnce)`](#fn-specsidecarscontainerswithstdinonce)
      * [`fn withTerminationMessagePath(terminationMessagePath)`](#fn-specsidecarscontainerswithterminationmessagepath)
      * [`fn withTerminationMessagePolicy(terminationMessagePolicy)`](#fn-specsidecarscontainerswithterminationmessagepolicy)
      * [`fn withTty(tty)`](#fn-specsidecarscontainerswithtty)
      * [`fn withVolumeDevices(volumeDevices)`](#fn-specsidecarscontainerswithvolumedevices)
      * [`fn withVolumeDevicesMixin(volumeDevices)`](#fn-specsidecarscontainerswithvolumedevicesmixin)
      * [`fn withVolumeMounts(volumeMounts)`](#fn-specsidecarscontainerswithvolumemounts)
      * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specsidecarscontainerswithvolumemountsmixin)
      * [`fn withWorkingDir(workingDir)`](#fn-specsidecarscontainerswithworkingdir)
      * [`obj spec.sideCars.containers.env`](#obj-specsidecarscontainersenv)
        * [`fn withName(name)`](#fn-specsidecarscontainersenvwithname)
        * [`fn withValue(value)`](#fn-specsidecarscontainersenvwithvalue)
        * [`obj spec.sideCars.containers.env.valueFrom`](#obj-specsidecarscontainersenvvaluefrom)
          * [`obj spec.sideCars.containers.env.valueFrom.configMapKeyRef`](#obj-specsidecarscontainersenvvaluefromconfigmapkeyref)
            * [`fn withKey(key)`](#fn-specsidecarscontainersenvvaluefromconfigmapkeyrefwithkey)
            * [`fn withName(name)`](#fn-specsidecarscontainersenvvaluefromconfigmapkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-specsidecarscontainersenvvaluefromconfigmapkeyrefwithoptional)
          * [`obj spec.sideCars.containers.env.valueFrom.fieldRef`](#obj-specsidecarscontainersenvvaluefromfieldref)
            * [`fn withApiVersion(apiVersion)`](#fn-specsidecarscontainersenvvaluefromfieldrefwithapiversion)
            * [`fn withFieldPath(fieldPath)`](#fn-specsidecarscontainersenvvaluefromfieldrefwithfieldpath)
          * [`obj spec.sideCars.containers.env.valueFrom.resourceFieldRef`](#obj-specsidecarscontainersenvvaluefromresourcefieldref)
            * [`fn withContainerName(containerName)`](#fn-specsidecarscontainersenvvaluefromresourcefieldrefwithcontainername)
            * [`fn withDivisor(divisor)`](#fn-specsidecarscontainersenvvaluefromresourcefieldrefwithdivisor)
            * [`fn withResource(resource)`](#fn-specsidecarscontainersenvvaluefromresourcefieldrefwithresource)
          * [`obj spec.sideCars.containers.env.valueFrom.secretKeyRef`](#obj-specsidecarscontainersenvvaluefromsecretkeyref)
            * [`fn withKey(key)`](#fn-specsidecarscontainersenvvaluefromsecretkeyrefwithkey)
            * [`fn withName(name)`](#fn-specsidecarscontainersenvvaluefromsecretkeyrefwithname)
            * [`fn withOptional(optional)`](#fn-specsidecarscontainersenvvaluefromsecretkeyrefwithoptional)
      * [`obj spec.sideCars.containers.envFrom`](#obj-specsidecarscontainersenvfrom)
        * [`fn withPrefix(prefix)`](#fn-specsidecarscontainersenvfromwithprefix)
        * [`obj spec.sideCars.containers.envFrom.configMapRef`](#obj-specsidecarscontainersenvfromconfigmapref)
          * [`fn withName(name)`](#fn-specsidecarscontainersenvfromconfigmaprefwithname)
          * [`fn withOptional(optional)`](#fn-specsidecarscontainersenvfromconfigmaprefwithoptional)
        * [`obj spec.sideCars.containers.envFrom.secretRef`](#obj-specsidecarscontainersenvfromsecretref)
          * [`fn withName(name)`](#fn-specsidecarscontainersenvfromsecretrefwithname)
          * [`fn withOptional(optional)`](#fn-specsidecarscontainersenvfromsecretrefwithoptional)
      * [`obj spec.sideCars.containers.lifecycle`](#obj-specsidecarscontainerslifecycle)
        * [`obj spec.sideCars.containers.lifecycle.postStart`](#obj-specsidecarscontainerslifecyclepoststart)
          * [`obj spec.sideCars.containers.lifecycle.postStart.exec`](#obj-specsidecarscontainerslifecyclepoststartexec)
            * [`fn withCommand(command)`](#fn-specsidecarscontainerslifecyclepoststartexecwithcommand)
            * [`fn withCommandMixin(command)`](#fn-specsidecarscontainerslifecyclepoststartexecwithcommandmixin)
          * [`obj spec.sideCars.containers.lifecycle.postStart.httpGet`](#obj-specsidecarscontainerslifecyclepoststarthttpget)
            * [`fn withHost(host)`](#fn-specsidecarscontainerslifecyclepoststarthttpgetwithhost)
            * [`fn withHttpHeaders(httpHeaders)`](#fn-specsidecarscontainerslifecyclepoststarthttpgetwithhttpheaders)
            * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specsidecarscontainerslifecyclepoststarthttpgetwithhttpheadersmixin)
            * [`fn withPath(path)`](#fn-specsidecarscontainerslifecyclepoststarthttpgetwithpath)
            * [`fn withPort(port)`](#fn-specsidecarscontainerslifecyclepoststarthttpgetwithport)
            * [`fn withScheme(scheme)`](#fn-specsidecarscontainerslifecyclepoststarthttpgetwithscheme)
            * [`obj spec.sideCars.containers.lifecycle.postStart.httpGet.httpHeaders`](#obj-specsidecarscontainerslifecyclepoststarthttpgethttpheaders)
              * [`fn withName(name)`](#fn-specsidecarscontainerslifecyclepoststarthttpgethttpheaderswithname)
              * [`fn withValue(value)`](#fn-specsidecarscontainerslifecyclepoststarthttpgethttpheaderswithvalue)
          * [`obj spec.sideCars.containers.lifecycle.postStart.sleep`](#obj-specsidecarscontainerslifecyclepoststartsleep)
            * [`fn withSeconds(seconds)`](#fn-specsidecarscontainerslifecyclepoststartsleepwithseconds)
          * [`obj spec.sideCars.containers.lifecycle.postStart.tcpSocket`](#obj-specsidecarscontainerslifecyclepoststarttcpsocket)
            * [`fn withHost(host)`](#fn-specsidecarscontainerslifecyclepoststarttcpsocketwithhost)
            * [`fn withPort(port)`](#fn-specsidecarscontainerslifecyclepoststarttcpsocketwithport)
        * [`obj spec.sideCars.containers.lifecycle.preStop`](#obj-specsidecarscontainerslifecycleprestop)
          * [`obj spec.sideCars.containers.lifecycle.preStop.exec`](#obj-specsidecarscontainerslifecycleprestopexec)
            * [`fn withCommand(command)`](#fn-specsidecarscontainerslifecycleprestopexecwithcommand)
            * [`fn withCommandMixin(command)`](#fn-specsidecarscontainerslifecycleprestopexecwithcommandmixin)
          * [`obj spec.sideCars.containers.lifecycle.preStop.httpGet`](#obj-specsidecarscontainerslifecycleprestophttpget)
            * [`fn withHost(host)`](#fn-specsidecarscontainerslifecycleprestophttpgetwithhost)
            * [`fn withHttpHeaders(httpHeaders)`](#fn-specsidecarscontainerslifecycleprestophttpgetwithhttpheaders)
            * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specsidecarscontainerslifecycleprestophttpgetwithhttpheadersmixin)
            * [`fn withPath(path)`](#fn-specsidecarscontainerslifecycleprestophttpgetwithpath)
            * [`fn withPort(port)`](#fn-specsidecarscontainerslifecycleprestophttpgetwithport)
            * [`fn withScheme(scheme)`](#fn-specsidecarscontainerslifecycleprestophttpgetwithscheme)
            * [`obj spec.sideCars.containers.lifecycle.preStop.httpGet.httpHeaders`](#obj-specsidecarscontainerslifecycleprestophttpgethttpheaders)
              * [`fn withName(name)`](#fn-specsidecarscontainerslifecycleprestophttpgethttpheaderswithname)
              * [`fn withValue(value)`](#fn-specsidecarscontainerslifecycleprestophttpgethttpheaderswithvalue)
          * [`obj spec.sideCars.containers.lifecycle.preStop.sleep`](#obj-specsidecarscontainerslifecycleprestopsleep)
            * [`fn withSeconds(seconds)`](#fn-specsidecarscontainerslifecycleprestopsleepwithseconds)
          * [`obj spec.sideCars.containers.lifecycle.preStop.tcpSocket`](#obj-specsidecarscontainerslifecycleprestoptcpsocket)
            * [`fn withHost(host)`](#fn-specsidecarscontainerslifecycleprestoptcpsocketwithhost)
            * [`fn withPort(port)`](#fn-specsidecarscontainerslifecycleprestoptcpsocketwithport)
      * [`obj spec.sideCars.containers.livenessProbe`](#obj-specsidecarscontainerslivenessprobe)
        * [`fn withFailureThreshold(failureThreshold)`](#fn-specsidecarscontainerslivenessprobewithfailurethreshold)
        * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specsidecarscontainerslivenessprobewithinitialdelayseconds)
        * [`fn withPeriodSeconds(periodSeconds)`](#fn-specsidecarscontainerslivenessprobewithperiodseconds)
        * [`fn withSuccessThreshold(successThreshold)`](#fn-specsidecarscontainerslivenessprobewithsuccessthreshold)
        * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specsidecarscontainerslivenessprobewithterminationgraceperiodseconds)
        * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specsidecarscontainerslivenessprobewithtimeoutseconds)
        * [`obj spec.sideCars.containers.livenessProbe.exec`](#obj-specsidecarscontainerslivenessprobeexec)
          * [`fn withCommand(command)`](#fn-specsidecarscontainerslivenessprobeexecwithcommand)
          * [`fn withCommandMixin(command)`](#fn-specsidecarscontainerslivenessprobeexecwithcommandmixin)
        * [`obj spec.sideCars.containers.livenessProbe.grpc`](#obj-specsidecarscontainerslivenessprobegrpc)
          * [`fn withPort(port)`](#fn-specsidecarscontainerslivenessprobegrpcwithport)
          * [`fn withService(service)`](#fn-specsidecarscontainerslivenessprobegrpcwithservice)
        * [`obj spec.sideCars.containers.livenessProbe.httpGet`](#obj-specsidecarscontainerslivenessprobehttpget)
          * [`fn withHost(host)`](#fn-specsidecarscontainerslivenessprobehttpgetwithhost)
          * [`fn withHttpHeaders(httpHeaders)`](#fn-specsidecarscontainerslivenessprobehttpgetwithhttpheaders)
          * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specsidecarscontainerslivenessprobehttpgetwithhttpheadersmixin)
          * [`fn withPath(path)`](#fn-specsidecarscontainerslivenessprobehttpgetwithpath)
          * [`fn withPort(port)`](#fn-specsidecarscontainerslivenessprobehttpgetwithport)
          * [`fn withScheme(scheme)`](#fn-specsidecarscontainerslivenessprobehttpgetwithscheme)
          * [`obj spec.sideCars.containers.livenessProbe.httpGet.httpHeaders`](#obj-specsidecarscontainerslivenessprobehttpgethttpheaders)
            * [`fn withName(name)`](#fn-specsidecarscontainerslivenessprobehttpgethttpheaderswithname)
            * [`fn withValue(value)`](#fn-specsidecarscontainerslivenessprobehttpgethttpheaderswithvalue)
        * [`obj spec.sideCars.containers.livenessProbe.tcpSocket`](#obj-specsidecarscontainerslivenessprobetcpsocket)
          * [`fn withHost(host)`](#fn-specsidecarscontainerslivenessprobetcpsocketwithhost)
          * [`fn withPort(port)`](#fn-specsidecarscontainerslivenessprobetcpsocketwithport)
      * [`obj spec.sideCars.containers.ports`](#obj-specsidecarscontainersports)
        * [`fn withContainerPort(containerPort)`](#fn-specsidecarscontainersportswithcontainerport)
        * [`fn withHostIP(hostIP)`](#fn-specsidecarscontainersportswithhostip)
        * [`fn withHostPort(hostPort)`](#fn-specsidecarscontainersportswithhostport)
        * [`fn withName(name)`](#fn-specsidecarscontainersportswithname)
        * [`fn withProtocol(protocol)`](#fn-specsidecarscontainersportswithprotocol)
      * [`obj spec.sideCars.containers.readinessProbe`](#obj-specsidecarscontainersreadinessprobe)
        * [`fn withFailureThreshold(failureThreshold)`](#fn-specsidecarscontainersreadinessprobewithfailurethreshold)
        * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specsidecarscontainersreadinessprobewithinitialdelayseconds)
        * [`fn withPeriodSeconds(periodSeconds)`](#fn-specsidecarscontainersreadinessprobewithperiodseconds)
        * [`fn withSuccessThreshold(successThreshold)`](#fn-specsidecarscontainersreadinessprobewithsuccessthreshold)
        * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specsidecarscontainersreadinessprobewithterminationgraceperiodseconds)
        * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specsidecarscontainersreadinessprobewithtimeoutseconds)
        * [`obj spec.sideCars.containers.readinessProbe.exec`](#obj-specsidecarscontainersreadinessprobeexec)
          * [`fn withCommand(command)`](#fn-specsidecarscontainersreadinessprobeexecwithcommand)
          * [`fn withCommandMixin(command)`](#fn-specsidecarscontainersreadinessprobeexecwithcommandmixin)
        * [`obj spec.sideCars.containers.readinessProbe.grpc`](#obj-specsidecarscontainersreadinessprobegrpc)
          * [`fn withPort(port)`](#fn-specsidecarscontainersreadinessprobegrpcwithport)
          * [`fn withService(service)`](#fn-specsidecarscontainersreadinessprobegrpcwithservice)
        * [`obj spec.sideCars.containers.readinessProbe.httpGet`](#obj-specsidecarscontainersreadinessprobehttpget)
          * [`fn withHost(host)`](#fn-specsidecarscontainersreadinessprobehttpgetwithhost)
          * [`fn withHttpHeaders(httpHeaders)`](#fn-specsidecarscontainersreadinessprobehttpgetwithhttpheaders)
          * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specsidecarscontainersreadinessprobehttpgetwithhttpheadersmixin)
          * [`fn withPath(path)`](#fn-specsidecarscontainersreadinessprobehttpgetwithpath)
          * [`fn withPort(port)`](#fn-specsidecarscontainersreadinessprobehttpgetwithport)
          * [`fn withScheme(scheme)`](#fn-specsidecarscontainersreadinessprobehttpgetwithscheme)
          * [`obj spec.sideCars.containers.readinessProbe.httpGet.httpHeaders`](#obj-specsidecarscontainersreadinessprobehttpgethttpheaders)
            * [`fn withName(name)`](#fn-specsidecarscontainersreadinessprobehttpgethttpheaderswithname)
            * [`fn withValue(value)`](#fn-specsidecarscontainersreadinessprobehttpgethttpheaderswithvalue)
        * [`obj spec.sideCars.containers.readinessProbe.tcpSocket`](#obj-specsidecarscontainersreadinessprobetcpsocket)
          * [`fn withHost(host)`](#fn-specsidecarscontainersreadinessprobetcpsocketwithhost)
          * [`fn withPort(port)`](#fn-specsidecarscontainersreadinessprobetcpsocketwithport)
      * [`obj spec.sideCars.containers.resizePolicy`](#obj-specsidecarscontainersresizepolicy)
        * [`fn withResourceName(resourceName)`](#fn-specsidecarscontainersresizepolicywithresourcename)
        * [`fn withRestartPolicy(restartPolicy)`](#fn-specsidecarscontainersresizepolicywithrestartpolicy)
      * [`obj spec.sideCars.containers.resources`](#obj-specsidecarscontainersresources)
        * [`fn withClaims(claims)`](#fn-specsidecarscontainersresourceswithclaims)
        * [`fn withClaimsMixin(claims)`](#fn-specsidecarscontainersresourceswithclaimsmixin)
        * [`fn withLimits(limits)`](#fn-specsidecarscontainersresourceswithlimits)
        * [`fn withLimitsMixin(limits)`](#fn-specsidecarscontainersresourceswithlimitsmixin)
        * [`fn withRequests(requests)`](#fn-specsidecarscontainersresourceswithrequests)
        * [`fn withRequestsMixin(requests)`](#fn-specsidecarscontainersresourceswithrequestsmixin)
        * [`obj spec.sideCars.containers.resources.claims`](#obj-specsidecarscontainersresourcesclaims)
          * [`fn withName(name)`](#fn-specsidecarscontainersresourcesclaimswithname)
      * [`obj spec.sideCars.containers.securityContext`](#obj-specsidecarscontainerssecuritycontext)
        * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-specsidecarscontainerssecuritycontextwithallowprivilegeescalation)
        * [`fn withPrivileged(privileged)`](#fn-specsidecarscontainerssecuritycontextwithprivileged)
        * [`fn withProcMount(procMount)`](#fn-specsidecarscontainerssecuritycontextwithprocmount)
        * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-specsidecarscontainerssecuritycontextwithreadonlyrootfilesystem)
        * [`fn withRunAsGroup(runAsGroup)`](#fn-specsidecarscontainerssecuritycontextwithrunasgroup)
        * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specsidecarscontainerssecuritycontextwithrunasnonroot)
        * [`fn withRunAsUser(runAsUser)`](#fn-specsidecarscontainerssecuritycontextwithrunasuser)
        * [`obj spec.sideCars.containers.securityContext.capabilities`](#obj-specsidecarscontainerssecuritycontextcapabilities)
          * [`fn withAdd(add)`](#fn-specsidecarscontainerssecuritycontextcapabilitieswithadd)
          * [`fn withAddMixin(add)`](#fn-specsidecarscontainerssecuritycontextcapabilitieswithaddmixin)
          * [`fn withDrop(drop)`](#fn-specsidecarscontainerssecuritycontextcapabilitieswithdrop)
          * [`fn withDropMixin(drop)`](#fn-specsidecarscontainerssecuritycontextcapabilitieswithdropmixin)
        * [`obj spec.sideCars.containers.securityContext.seLinuxOptions`](#obj-specsidecarscontainerssecuritycontextselinuxoptions)
          * [`fn withLevel(level)`](#fn-specsidecarscontainerssecuritycontextselinuxoptionswithlevel)
          * [`fn withRole(role)`](#fn-specsidecarscontainerssecuritycontextselinuxoptionswithrole)
          * [`fn withType(type)`](#fn-specsidecarscontainerssecuritycontextselinuxoptionswithtype)
          * [`fn withUser(user)`](#fn-specsidecarscontainerssecuritycontextselinuxoptionswithuser)
        * [`obj spec.sideCars.containers.securityContext.seccompProfile`](#obj-specsidecarscontainerssecuritycontextseccompprofile)
          * [`fn withLocalhostProfile(localhostProfile)`](#fn-specsidecarscontainerssecuritycontextseccompprofilewithlocalhostprofile)
          * [`fn withType(type)`](#fn-specsidecarscontainerssecuritycontextseccompprofilewithtype)
        * [`obj spec.sideCars.containers.securityContext.windowsOptions`](#obj-specsidecarscontainerssecuritycontextwindowsoptions)
          * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specsidecarscontainerssecuritycontextwindowsoptionswithgmsacredentialspec)
          * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specsidecarscontainerssecuritycontextwindowsoptionswithgmsacredentialspecname)
          * [`fn withHostProcess(hostProcess)`](#fn-specsidecarscontainerssecuritycontextwindowsoptionswithhostprocess)
          * [`fn withRunAsUserName(runAsUserName)`](#fn-specsidecarscontainerssecuritycontextwindowsoptionswithrunasusername)
      * [`obj spec.sideCars.containers.startupProbe`](#obj-specsidecarscontainersstartupprobe)
        * [`fn withFailureThreshold(failureThreshold)`](#fn-specsidecarscontainersstartupprobewithfailurethreshold)
        * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specsidecarscontainersstartupprobewithinitialdelayseconds)
        * [`fn withPeriodSeconds(periodSeconds)`](#fn-specsidecarscontainersstartupprobewithperiodseconds)
        * [`fn withSuccessThreshold(successThreshold)`](#fn-specsidecarscontainersstartupprobewithsuccessthreshold)
        * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specsidecarscontainersstartupprobewithterminationgraceperiodseconds)
        * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specsidecarscontainersstartupprobewithtimeoutseconds)
        * [`obj spec.sideCars.containers.startupProbe.exec`](#obj-specsidecarscontainersstartupprobeexec)
          * [`fn withCommand(command)`](#fn-specsidecarscontainersstartupprobeexecwithcommand)
          * [`fn withCommandMixin(command)`](#fn-specsidecarscontainersstartupprobeexecwithcommandmixin)
        * [`obj spec.sideCars.containers.startupProbe.grpc`](#obj-specsidecarscontainersstartupprobegrpc)
          * [`fn withPort(port)`](#fn-specsidecarscontainersstartupprobegrpcwithport)
          * [`fn withService(service)`](#fn-specsidecarscontainersstartupprobegrpcwithservice)
        * [`obj spec.sideCars.containers.startupProbe.httpGet`](#obj-specsidecarscontainersstartupprobehttpget)
          * [`fn withHost(host)`](#fn-specsidecarscontainersstartupprobehttpgetwithhost)
          * [`fn withHttpHeaders(httpHeaders)`](#fn-specsidecarscontainersstartupprobehttpgetwithhttpheaders)
          * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specsidecarscontainersstartupprobehttpgetwithhttpheadersmixin)
          * [`fn withPath(path)`](#fn-specsidecarscontainersstartupprobehttpgetwithpath)
          * [`fn withPort(port)`](#fn-specsidecarscontainersstartupprobehttpgetwithport)
          * [`fn withScheme(scheme)`](#fn-specsidecarscontainersstartupprobehttpgetwithscheme)
          * [`obj spec.sideCars.containers.startupProbe.httpGet.httpHeaders`](#obj-specsidecarscontainersstartupprobehttpgethttpheaders)
            * [`fn withName(name)`](#fn-specsidecarscontainersstartupprobehttpgethttpheaderswithname)
            * [`fn withValue(value)`](#fn-specsidecarscontainersstartupprobehttpgethttpheaderswithvalue)
        * [`obj spec.sideCars.containers.startupProbe.tcpSocket`](#obj-specsidecarscontainersstartupprobetcpsocket)
          * [`fn withHost(host)`](#fn-specsidecarscontainersstartupprobetcpsocketwithhost)
          * [`fn withPort(port)`](#fn-specsidecarscontainersstartupprobetcpsocketwithport)
      * [`obj spec.sideCars.containers.volumeDevices`](#obj-specsidecarscontainersvolumedevices)
        * [`fn withDevicePath(devicePath)`](#fn-specsidecarscontainersvolumedeviceswithdevicepath)
        * [`fn withName(name)`](#fn-specsidecarscontainersvolumedeviceswithname)
      * [`obj spec.sideCars.containers.volumeMounts`](#obj-specsidecarscontainersvolumemounts)
        * [`fn withMountPath(mountPath)`](#fn-specsidecarscontainersvolumemountswithmountpath)
        * [`fn withMountPropagation(mountPropagation)`](#fn-specsidecarscontainersvolumemountswithmountpropagation)
        * [`fn withName(name)`](#fn-specsidecarscontainersvolumemountswithname)
        * [`fn withReadOnly(readOnly)`](#fn-specsidecarscontainersvolumemountswithreadonly)
        * [`fn withSubPath(subPath)`](#fn-specsidecarscontainersvolumemountswithsubpath)
        * [`fn withSubPathExpr(subPathExpr)`](#fn-specsidecarscontainersvolumemountswithsubpathexpr)
    * [`obj spec.sideCars.resources`](#obj-specsidecarsresources)
      * [`fn withClaims(claims)`](#fn-specsidecarsresourceswithclaims)
      * [`fn withClaimsMixin(claims)`](#fn-specsidecarsresourceswithclaimsmixin)
      * [`fn withLimits(limits)`](#fn-specsidecarsresourceswithlimits)
      * [`fn withLimitsMixin(limits)`](#fn-specsidecarsresourceswithlimitsmixin)
      * [`fn withRequests(requests)`](#fn-specsidecarsresourceswithrequests)
      * [`fn withRequestsMixin(requests)`](#fn-specsidecarsresourceswithrequestsmixin)
      * [`obj spec.sideCars.resources.claims`](#obj-specsidecarsresourcesclaims)
        * [`fn withName(name)`](#fn-specsidecarsresourcesclaimswithname)
    * [`obj spec.sideCars.volumeClaimTemplates`](#obj-specsidecarsvolumeclaimtemplates)
      * [`fn withApiVersion(apiVersion)`](#fn-specsidecarsvolumeclaimtemplateswithapiversion)
      * [`fn withKind(kind)`](#fn-specsidecarsvolumeclaimtemplateswithkind)
      * [`obj spec.sideCars.volumeClaimTemplates.metadata`](#obj-specsidecarsvolumeclaimtemplatesmetadata)
        * [`fn withAnnotations(annotations)`](#fn-specsidecarsvolumeclaimtemplatesmetadatawithannotations)
        * [`fn withAnnotationsMixin(annotations)`](#fn-specsidecarsvolumeclaimtemplatesmetadatawithannotationsmixin)
        * [`fn withFinalizers(finalizers)`](#fn-specsidecarsvolumeclaimtemplatesmetadatawithfinalizers)
        * [`fn withFinalizersMixin(finalizers)`](#fn-specsidecarsvolumeclaimtemplatesmetadatawithfinalizersmixin)
        * [`fn withLabels(labels)`](#fn-specsidecarsvolumeclaimtemplatesmetadatawithlabels)
        * [`fn withLabelsMixin(labels)`](#fn-specsidecarsvolumeclaimtemplatesmetadatawithlabelsmixin)
        * [`fn withName(name)`](#fn-specsidecarsvolumeclaimtemplatesmetadatawithname)
        * [`fn withNamespace(namespace)`](#fn-specsidecarsvolumeclaimtemplatesmetadatawithnamespace)
      * [`obj spec.sideCars.volumeClaimTemplates.spec`](#obj-specsidecarsvolumeclaimtemplatesspec)
        * [`fn withAccessModes(accessModes)`](#fn-specsidecarsvolumeclaimtemplatesspecwithaccessmodes)
        * [`fn withAccessModesMixin(accessModes)`](#fn-specsidecarsvolumeclaimtemplatesspecwithaccessmodesmixin)
        * [`fn withStorageClassName(storageClassName)`](#fn-specsidecarsvolumeclaimtemplatesspecwithstorageclassname)
        * [`fn withVolumeAttributesClassName(volumeAttributesClassName)`](#fn-specsidecarsvolumeclaimtemplatesspecwithvolumeattributesclassname)
        * [`fn withVolumeMode(volumeMode)`](#fn-specsidecarsvolumeclaimtemplatesspecwithvolumemode)
        * [`fn withVolumeName(volumeName)`](#fn-specsidecarsvolumeclaimtemplatesspecwithvolumename)
        * [`obj spec.sideCars.volumeClaimTemplates.spec.dataSource`](#obj-specsidecarsvolumeclaimtemplatesspecdatasource)
          * [`fn withApiGroup(apiGroup)`](#fn-specsidecarsvolumeclaimtemplatesspecdatasourcewithapigroup)
          * [`fn withKind(kind)`](#fn-specsidecarsvolumeclaimtemplatesspecdatasourcewithkind)
          * [`fn withName(name)`](#fn-specsidecarsvolumeclaimtemplatesspecdatasourcewithname)
        * [`obj spec.sideCars.volumeClaimTemplates.spec.dataSourceRef`](#obj-specsidecarsvolumeclaimtemplatesspecdatasourceref)
          * [`fn withApiGroup(apiGroup)`](#fn-specsidecarsvolumeclaimtemplatesspecdatasourcerefwithapigroup)
          * [`fn withKind(kind)`](#fn-specsidecarsvolumeclaimtemplatesspecdatasourcerefwithkind)
          * [`fn withName(name)`](#fn-specsidecarsvolumeclaimtemplatesspecdatasourcerefwithname)
          * [`fn withNamespace(namespace)`](#fn-specsidecarsvolumeclaimtemplatesspecdatasourcerefwithnamespace)
        * [`obj spec.sideCars.volumeClaimTemplates.spec.resources`](#obj-specsidecarsvolumeclaimtemplatesspecresources)
          * [`fn withLimits(limits)`](#fn-specsidecarsvolumeclaimtemplatesspecresourceswithlimits)
          * [`fn withLimitsMixin(limits)`](#fn-specsidecarsvolumeclaimtemplatesspecresourceswithlimitsmixin)
          * [`fn withRequests(requests)`](#fn-specsidecarsvolumeclaimtemplatesspecresourceswithrequests)
          * [`fn withRequestsMixin(requests)`](#fn-specsidecarsvolumeclaimtemplatesspecresourceswithrequestsmixin)
        * [`obj spec.sideCars.volumeClaimTemplates.spec.selector`](#obj-specsidecarsvolumeclaimtemplatesspecselector)
          * [`fn withMatchExpressions(matchExpressions)`](#fn-specsidecarsvolumeclaimtemplatesspecselectorwithmatchexpressions)
          * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specsidecarsvolumeclaimtemplatesspecselectorwithmatchexpressionsmixin)
          * [`fn withMatchLabels(matchLabels)`](#fn-specsidecarsvolumeclaimtemplatesspecselectorwithmatchlabels)
          * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specsidecarsvolumeclaimtemplatesspecselectorwithmatchlabelsmixin)
          * [`obj spec.sideCars.volumeClaimTemplates.spec.selector.matchExpressions`](#obj-specsidecarsvolumeclaimtemplatesspecselectormatchexpressions)
            * [`fn withKey(key)`](#fn-specsidecarsvolumeclaimtemplatesspecselectormatchexpressionswithkey)
            * [`fn withOperator(operator)`](#fn-specsidecarsvolumeclaimtemplatesspecselectormatchexpressionswithoperator)
            * [`fn withValues(values)`](#fn-specsidecarsvolumeclaimtemplatesspecselectormatchexpressionswithvalues)
            * [`fn withValuesMixin(values)`](#fn-specsidecarsvolumeclaimtemplatesspecselectormatchexpressionswithvaluesmixin)
    * [`obj spec.sideCars.volumes`](#obj-specsidecarsvolumes)
      * [`fn withName(name)`](#fn-specsidecarsvolumeswithname)
      * [`obj spec.sideCars.volumes.awsElasticBlockStore`](#obj-specsidecarsvolumesawselasticblockstore)
        * [`fn withFsType(fsType)`](#fn-specsidecarsvolumesawselasticblockstorewithfstype)
        * [`fn withPartition(partition)`](#fn-specsidecarsvolumesawselasticblockstorewithpartition)
        * [`fn withReadOnly(readOnly)`](#fn-specsidecarsvolumesawselasticblockstorewithreadonly)
        * [`fn withVolumeID(volumeID)`](#fn-specsidecarsvolumesawselasticblockstorewithvolumeid)
      * [`obj spec.sideCars.volumes.azureDisk`](#obj-specsidecarsvolumesazuredisk)
        * [`fn withCachingMode(cachingMode)`](#fn-specsidecarsvolumesazurediskwithcachingmode)
        * [`fn withDiskName(diskName)`](#fn-specsidecarsvolumesazurediskwithdiskname)
        * [`fn withDiskURI(diskURI)`](#fn-specsidecarsvolumesazurediskwithdiskuri)
        * [`fn withFsType(fsType)`](#fn-specsidecarsvolumesazurediskwithfstype)
        * [`fn withKind(kind)`](#fn-specsidecarsvolumesazurediskwithkind)
        * [`fn withReadOnly(readOnly)`](#fn-specsidecarsvolumesazurediskwithreadonly)
      * [`obj spec.sideCars.volumes.azureFile`](#obj-specsidecarsvolumesazurefile)
        * [`fn withReadOnly(readOnly)`](#fn-specsidecarsvolumesazurefilewithreadonly)
        * [`fn withSecretName(secretName)`](#fn-specsidecarsvolumesazurefilewithsecretname)
        * [`fn withShareName(shareName)`](#fn-specsidecarsvolumesazurefilewithsharename)
      * [`obj spec.sideCars.volumes.cephfs`](#obj-specsidecarsvolumescephfs)
        * [`fn withMonitors(monitors)`](#fn-specsidecarsvolumescephfswithmonitors)
        * [`fn withMonitorsMixin(monitors)`](#fn-specsidecarsvolumescephfswithmonitorsmixin)
        * [`fn withPath(path)`](#fn-specsidecarsvolumescephfswithpath)
        * [`fn withReadOnly(readOnly)`](#fn-specsidecarsvolumescephfswithreadonly)
        * [`fn withSecretFile(secretFile)`](#fn-specsidecarsvolumescephfswithsecretfile)
        * [`fn withUser(user)`](#fn-specsidecarsvolumescephfswithuser)
        * [`obj spec.sideCars.volumes.cephfs.secretRef`](#obj-specsidecarsvolumescephfssecretref)
          * [`fn withName(name)`](#fn-specsidecarsvolumescephfssecretrefwithname)
      * [`obj spec.sideCars.volumes.cinder`](#obj-specsidecarsvolumescinder)
        * [`fn withFsType(fsType)`](#fn-specsidecarsvolumescinderwithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-specsidecarsvolumescinderwithreadonly)
        * [`fn withVolumeID(volumeID)`](#fn-specsidecarsvolumescinderwithvolumeid)
        * [`obj spec.sideCars.volumes.cinder.secretRef`](#obj-specsidecarsvolumescindersecretref)
          * [`fn withName(name)`](#fn-specsidecarsvolumescindersecretrefwithname)
      * [`obj spec.sideCars.volumes.configMap`](#obj-specsidecarsvolumesconfigmap)
        * [`fn withDefaultMode(defaultMode)`](#fn-specsidecarsvolumesconfigmapwithdefaultmode)
        * [`fn withItems(items)`](#fn-specsidecarsvolumesconfigmapwithitems)
        * [`fn withItemsMixin(items)`](#fn-specsidecarsvolumesconfigmapwithitemsmixin)
        * [`fn withName(name)`](#fn-specsidecarsvolumesconfigmapwithname)
        * [`fn withOptional(optional)`](#fn-specsidecarsvolumesconfigmapwithoptional)
        * [`obj spec.sideCars.volumes.configMap.items`](#obj-specsidecarsvolumesconfigmapitems)
          * [`fn withKey(key)`](#fn-specsidecarsvolumesconfigmapitemswithkey)
          * [`fn withMode(mode)`](#fn-specsidecarsvolumesconfigmapitemswithmode)
          * [`fn withPath(path)`](#fn-specsidecarsvolumesconfigmapitemswithpath)
      * [`obj spec.sideCars.volumes.csi`](#obj-specsidecarsvolumescsi)
        * [`fn withDriver(driver)`](#fn-specsidecarsvolumescsiwithdriver)
        * [`fn withFsType(fsType)`](#fn-specsidecarsvolumescsiwithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-specsidecarsvolumescsiwithreadonly)
        * [`fn withVolumeAttributes(volumeAttributes)`](#fn-specsidecarsvolumescsiwithvolumeattributes)
        * [`fn withVolumeAttributesMixin(volumeAttributes)`](#fn-specsidecarsvolumescsiwithvolumeattributesmixin)
        * [`obj spec.sideCars.volumes.csi.nodePublishSecretRef`](#obj-specsidecarsvolumescsinodepublishsecretref)
          * [`fn withName(name)`](#fn-specsidecarsvolumescsinodepublishsecretrefwithname)
      * [`obj spec.sideCars.volumes.downwardAPI`](#obj-specsidecarsvolumesdownwardapi)
        * [`fn withDefaultMode(defaultMode)`](#fn-specsidecarsvolumesdownwardapiwithdefaultmode)
        * [`fn withItems(items)`](#fn-specsidecarsvolumesdownwardapiwithitems)
        * [`fn withItemsMixin(items)`](#fn-specsidecarsvolumesdownwardapiwithitemsmixin)
        * [`obj spec.sideCars.volumes.downwardAPI.items`](#obj-specsidecarsvolumesdownwardapiitems)
          * [`fn withMode(mode)`](#fn-specsidecarsvolumesdownwardapiitemswithmode)
          * [`fn withPath(path)`](#fn-specsidecarsvolumesdownwardapiitemswithpath)
          * [`obj spec.sideCars.volumes.downwardAPI.items.fieldRef`](#obj-specsidecarsvolumesdownwardapiitemsfieldref)
            * [`fn withApiVersion(apiVersion)`](#fn-specsidecarsvolumesdownwardapiitemsfieldrefwithapiversion)
            * [`fn withFieldPath(fieldPath)`](#fn-specsidecarsvolumesdownwardapiitemsfieldrefwithfieldpath)
          * [`obj spec.sideCars.volumes.downwardAPI.items.resourceFieldRef`](#obj-specsidecarsvolumesdownwardapiitemsresourcefieldref)
            * [`fn withContainerName(containerName)`](#fn-specsidecarsvolumesdownwardapiitemsresourcefieldrefwithcontainername)
            * [`fn withDivisor(divisor)`](#fn-specsidecarsvolumesdownwardapiitemsresourcefieldrefwithdivisor)
            * [`fn withResource(resource)`](#fn-specsidecarsvolumesdownwardapiitemsresourcefieldrefwithresource)
      * [`obj spec.sideCars.volumes.emptyDir`](#obj-specsidecarsvolumesemptydir)
        * [`fn withMedium(medium)`](#fn-specsidecarsvolumesemptydirwithmedium)
        * [`fn withSizeLimit(sizeLimit)`](#fn-specsidecarsvolumesemptydirwithsizelimit)
      * [`obj spec.sideCars.volumes.ephemeral`](#obj-specsidecarsvolumesephemeral)
        * [`obj spec.sideCars.volumes.ephemeral.volumeClaimTemplate`](#obj-specsidecarsvolumesephemeralvolumeclaimtemplate)
          * [`obj spec.sideCars.volumes.ephemeral.volumeClaimTemplate.metadata`](#obj-specsidecarsvolumesephemeralvolumeclaimtemplatemetadata)
            * [`fn withAnnotations(annotations)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatemetadatawithannotations)
            * [`fn withAnnotationsMixin(annotations)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatemetadatawithannotationsmixin)
            * [`fn withFinalizers(finalizers)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatemetadatawithfinalizers)
            * [`fn withFinalizersMixin(finalizers)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatemetadatawithfinalizersmixin)
            * [`fn withLabels(labels)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatemetadatawithlabels)
            * [`fn withLabelsMixin(labels)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatemetadatawithlabelsmixin)
            * [`fn withName(name)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatemetadatawithname)
            * [`fn withNamespace(namespace)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatemetadatawithnamespace)
          * [`obj spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec`](#obj-specsidecarsvolumesephemeralvolumeclaimtemplatespec)
            * [`fn withAccessModes(accessModes)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecwithaccessmodes)
            * [`fn withAccessModesMixin(accessModes)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecwithaccessmodesmixin)
            * [`fn withStorageClassName(storageClassName)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecwithstorageclassname)
            * [`fn withVolumeAttributesClassName(volumeAttributesClassName)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecwithvolumeattributesclassname)
            * [`fn withVolumeMode(volumeMode)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecwithvolumemode)
            * [`fn withVolumeName(volumeName)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecwithvolumename)
            * [`obj spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.dataSource`](#obj-specsidecarsvolumesephemeralvolumeclaimtemplatespecdatasource)
              * [`fn withApiGroup(apiGroup)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecdatasourcewithapigroup)
              * [`fn withKind(kind)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecdatasourcewithkind)
              * [`fn withName(name)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecdatasourcewithname)
            * [`obj spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef`](#obj-specsidecarsvolumesephemeralvolumeclaimtemplatespecdatasourceref)
              * [`fn withApiGroup(apiGroup)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithapigroup)
              * [`fn withKind(kind)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithkind)
              * [`fn withName(name)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithname)
              * [`fn withNamespace(namespace)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithnamespace)
            * [`obj spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.resources`](#obj-specsidecarsvolumesephemeralvolumeclaimtemplatespecresources)
              * [`fn withLimits(limits)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecresourceswithlimits)
              * [`fn withLimitsMixin(limits)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecresourceswithlimitsmixin)
              * [`fn withRequests(requests)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecresourceswithrequests)
              * [`fn withRequestsMixin(requests)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecresourceswithrequestsmixin)
            * [`obj spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.selector`](#obj-specsidecarsvolumesephemeralvolumeclaimtemplatespecselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabelsmixin)
              * [`obj spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions`](#obj-specsidecarsvolumesephemeralvolumeclaimtemplatespecselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specsidecarsvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvaluesmixin)
      * [`obj spec.sideCars.volumes.fc`](#obj-specsidecarsvolumesfc)
        * [`fn withFsType(fsType)`](#fn-specsidecarsvolumesfcwithfstype)
        * [`fn withLun(lun)`](#fn-specsidecarsvolumesfcwithlun)
        * [`fn withReadOnly(readOnly)`](#fn-specsidecarsvolumesfcwithreadonly)
        * [`fn withTargetWWNs(targetWWNs)`](#fn-specsidecarsvolumesfcwithtargetwwns)
        * [`fn withTargetWWNsMixin(targetWWNs)`](#fn-specsidecarsvolumesfcwithtargetwwnsmixin)
        * [`fn withWwids(wwids)`](#fn-specsidecarsvolumesfcwithwwids)
        * [`fn withWwidsMixin(wwids)`](#fn-specsidecarsvolumesfcwithwwidsmixin)
      * [`obj spec.sideCars.volumes.flexVolume`](#obj-specsidecarsvolumesflexvolume)
        * [`fn withDriver(driver)`](#fn-specsidecarsvolumesflexvolumewithdriver)
        * [`fn withFsType(fsType)`](#fn-specsidecarsvolumesflexvolumewithfstype)
        * [`fn withOptions(options)`](#fn-specsidecarsvolumesflexvolumewithoptions)
        * [`fn withOptionsMixin(options)`](#fn-specsidecarsvolumesflexvolumewithoptionsmixin)
        * [`fn withReadOnly(readOnly)`](#fn-specsidecarsvolumesflexvolumewithreadonly)
        * [`obj spec.sideCars.volumes.flexVolume.secretRef`](#obj-specsidecarsvolumesflexvolumesecretref)
          * [`fn withName(name)`](#fn-specsidecarsvolumesflexvolumesecretrefwithname)
      * [`obj spec.sideCars.volumes.flocker`](#obj-specsidecarsvolumesflocker)
        * [`fn withDatasetName(datasetName)`](#fn-specsidecarsvolumesflockerwithdatasetname)
        * [`fn withDatasetUUID(datasetUUID)`](#fn-specsidecarsvolumesflockerwithdatasetuuid)
      * [`obj spec.sideCars.volumes.gcePersistentDisk`](#obj-specsidecarsvolumesgcepersistentdisk)
        * [`fn withFsType(fsType)`](#fn-specsidecarsvolumesgcepersistentdiskwithfstype)
        * [`fn withPartition(partition)`](#fn-specsidecarsvolumesgcepersistentdiskwithpartition)
        * [`fn withPdName(pdName)`](#fn-specsidecarsvolumesgcepersistentdiskwithpdname)
        * [`fn withReadOnly(readOnly)`](#fn-specsidecarsvolumesgcepersistentdiskwithreadonly)
      * [`obj spec.sideCars.volumes.gitRepo`](#obj-specsidecarsvolumesgitrepo)
        * [`fn withDirectory(directory)`](#fn-specsidecarsvolumesgitrepowithdirectory)
        * [`fn withRepository(repository)`](#fn-specsidecarsvolumesgitrepowithrepository)
        * [`fn withRevision(revision)`](#fn-specsidecarsvolumesgitrepowithrevision)
      * [`obj spec.sideCars.volumes.glusterfs`](#obj-specsidecarsvolumesglusterfs)
        * [`fn withEndpoints(endpoints)`](#fn-specsidecarsvolumesglusterfswithendpoints)
        * [`fn withPath(path)`](#fn-specsidecarsvolumesglusterfswithpath)
        * [`fn withReadOnly(readOnly)`](#fn-specsidecarsvolumesglusterfswithreadonly)
      * [`obj spec.sideCars.volumes.hostPath`](#obj-specsidecarsvolumeshostpath)
        * [`fn withPath(path)`](#fn-specsidecarsvolumeshostpathwithpath)
        * [`fn withType(type)`](#fn-specsidecarsvolumeshostpathwithtype)
      * [`obj spec.sideCars.volumes.iscsi`](#obj-specsidecarsvolumesiscsi)
        * [`fn withChapAuthDiscovery(chapAuthDiscovery)`](#fn-specsidecarsvolumesiscsiwithchapauthdiscovery)
        * [`fn withChapAuthSession(chapAuthSession)`](#fn-specsidecarsvolumesiscsiwithchapauthsession)
        * [`fn withFsType(fsType)`](#fn-specsidecarsvolumesiscsiwithfstype)
        * [`fn withInitiatorName(initiatorName)`](#fn-specsidecarsvolumesiscsiwithinitiatorname)
        * [`fn withIqn(iqn)`](#fn-specsidecarsvolumesiscsiwithiqn)
        * [`fn withIscsiInterface(iscsiInterface)`](#fn-specsidecarsvolumesiscsiwithiscsiinterface)
        * [`fn withLun(lun)`](#fn-specsidecarsvolumesiscsiwithlun)
        * [`fn withPortals(portals)`](#fn-specsidecarsvolumesiscsiwithportals)
        * [`fn withPortalsMixin(portals)`](#fn-specsidecarsvolumesiscsiwithportalsmixin)
        * [`fn withReadOnly(readOnly)`](#fn-specsidecarsvolumesiscsiwithreadonly)
        * [`fn withTargetPortal(targetPortal)`](#fn-specsidecarsvolumesiscsiwithtargetportal)
        * [`obj spec.sideCars.volumes.iscsi.secretRef`](#obj-specsidecarsvolumesiscsisecretref)
          * [`fn withName(name)`](#fn-specsidecarsvolumesiscsisecretrefwithname)
      * [`obj spec.sideCars.volumes.nfs`](#obj-specsidecarsvolumesnfs)
        * [`fn withPath(path)`](#fn-specsidecarsvolumesnfswithpath)
        * [`fn withReadOnly(readOnly)`](#fn-specsidecarsvolumesnfswithreadonly)
        * [`fn withServer(server)`](#fn-specsidecarsvolumesnfswithserver)
      * [`obj spec.sideCars.volumes.persistentVolumeClaim`](#obj-specsidecarsvolumespersistentvolumeclaim)
        * [`fn withClaimName(claimName)`](#fn-specsidecarsvolumespersistentvolumeclaimwithclaimname)
        * [`fn withReadOnly(readOnly)`](#fn-specsidecarsvolumespersistentvolumeclaimwithreadonly)
      * [`obj spec.sideCars.volumes.photonPersistentDisk`](#obj-specsidecarsvolumesphotonpersistentdisk)
        * [`fn withFsType(fsType)`](#fn-specsidecarsvolumesphotonpersistentdiskwithfstype)
        * [`fn withPdID(pdID)`](#fn-specsidecarsvolumesphotonpersistentdiskwithpdid)
      * [`obj spec.sideCars.volumes.portworxVolume`](#obj-specsidecarsvolumesportworxvolume)
        * [`fn withFsType(fsType)`](#fn-specsidecarsvolumesportworxvolumewithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-specsidecarsvolumesportworxvolumewithreadonly)
        * [`fn withVolumeID(volumeID)`](#fn-specsidecarsvolumesportworxvolumewithvolumeid)
      * [`obj spec.sideCars.volumes.projected`](#obj-specsidecarsvolumesprojected)
        * [`fn withDefaultMode(defaultMode)`](#fn-specsidecarsvolumesprojectedwithdefaultmode)
        * [`fn withSources(sources)`](#fn-specsidecarsvolumesprojectedwithsources)
        * [`fn withSourcesMixin(sources)`](#fn-specsidecarsvolumesprojectedwithsourcesmixin)
        * [`obj spec.sideCars.volumes.projected.sources`](#obj-specsidecarsvolumesprojectedsources)
          * [`obj spec.sideCars.volumes.projected.sources.clusterTrustBundle`](#obj-specsidecarsvolumesprojectedsourcesclustertrustbundle)
            * [`fn withName(name)`](#fn-specsidecarsvolumesprojectedsourcesclustertrustbundlewithname)
            * [`fn withOptional(optional)`](#fn-specsidecarsvolumesprojectedsourcesclustertrustbundlewithoptional)
            * [`fn withPath(path)`](#fn-specsidecarsvolumesprojectedsourcesclustertrustbundlewithpath)
            * [`fn withSignerName(signerName)`](#fn-specsidecarsvolumesprojectedsourcesclustertrustbundlewithsignername)
            * [`obj spec.sideCars.volumes.projected.sources.clusterTrustBundle.labelSelector`](#obj-specsidecarsvolumesprojectedsourcesclustertrustbundlelabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specsidecarsvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specsidecarsvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specsidecarsvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specsidecarsvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabelsmixin)
              * [`obj spec.sideCars.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions`](#obj-specsidecarsvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specsidecarsvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specsidecarsvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specsidecarsvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specsidecarsvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.sideCars.volumes.projected.sources.configMap`](#obj-specsidecarsvolumesprojectedsourcesconfigmap)
            * [`fn withItems(items)`](#fn-specsidecarsvolumesprojectedsourcesconfigmapwithitems)
            * [`fn withItemsMixin(items)`](#fn-specsidecarsvolumesprojectedsourcesconfigmapwithitemsmixin)
            * [`fn withName(name)`](#fn-specsidecarsvolumesprojectedsourcesconfigmapwithname)
            * [`fn withOptional(optional)`](#fn-specsidecarsvolumesprojectedsourcesconfigmapwithoptional)
            * [`obj spec.sideCars.volumes.projected.sources.configMap.items`](#obj-specsidecarsvolumesprojectedsourcesconfigmapitems)
              * [`fn withKey(key)`](#fn-specsidecarsvolumesprojectedsourcesconfigmapitemswithkey)
              * [`fn withMode(mode)`](#fn-specsidecarsvolumesprojectedsourcesconfigmapitemswithmode)
              * [`fn withPath(path)`](#fn-specsidecarsvolumesprojectedsourcesconfigmapitemswithpath)
          * [`obj spec.sideCars.volumes.projected.sources.downwardAPI`](#obj-specsidecarsvolumesprojectedsourcesdownwardapi)
            * [`fn withItems(items)`](#fn-specsidecarsvolumesprojectedsourcesdownwardapiwithitems)
            * [`fn withItemsMixin(items)`](#fn-specsidecarsvolumesprojectedsourcesdownwardapiwithitemsmixin)
            * [`obj spec.sideCars.volumes.projected.sources.downwardAPI.items`](#obj-specsidecarsvolumesprojectedsourcesdownwardapiitems)
              * [`fn withMode(mode)`](#fn-specsidecarsvolumesprojectedsourcesdownwardapiitemswithmode)
              * [`fn withPath(path)`](#fn-specsidecarsvolumesprojectedsourcesdownwardapiitemswithpath)
              * [`obj spec.sideCars.volumes.projected.sources.downwardAPI.items.fieldRef`](#obj-specsidecarsvolumesprojectedsourcesdownwardapiitemsfieldref)
                * [`fn withApiVersion(apiVersion)`](#fn-specsidecarsvolumesprojectedsourcesdownwardapiitemsfieldrefwithapiversion)
                * [`fn withFieldPath(fieldPath)`](#fn-specsidecarsvolumesprojectedsourcesdownwardapiitemsfieldrefwithfieldpath)
              * [`obj spec.sideCars.volumes.projected.sources.downwardAPI.items.resourceFieldRef`](#obj-specsidecarsvolumesprojectedsourcesdownwardapiitemsresourcefieldref)
                * [`fn withContainerName(containerName)`](#fn-specsidecarsvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithcontainername)
                * [`fn withDivisor(divisor)`](#fn-specsidecarsvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithdivisor)
                * [`fn withResource(resource)`](#fn-specsidecarsvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithresource)
          * [`obj spec.sideCars.volumes.projected.sources.secret`](#obj-specsidecarsvolumesprojectedsourcessecret)
            * [`fn withItems(items)`](#fn-specsidecarsvolumesprojectedsourcessecretwithitems)
            * [`fn withItemsMixin(items)`](#fn-specsidecarsvolumesprojectedsourcessecretwithitemsmixin)
            * [`fn withName(name)`](#fn-specsidecarsvolumesprojectedsourcessecretwithname)
            * [`fn withOptional(optional)`](#fn-specsidecarsvolumesprojectedsourcessecretwithoptional)
            * [`obj spec.sideCars.volumes.projected.sources.secret.items`](#obj-specsidecarsvolumesprojectedsourcessecretitems)
              * [`fn withKey(key)`](#fn-specsidecarsvolumesprojectedsourcessecretitemswithkey)
              * [`fn withMode(mode)`](#fn-specsidecarsvolumesprojectedsourcessecretitemswithmode)
              * [`fn withPath(path)`](#fn-specsidecarsvolumesprojectedsourcessecretitemswithpath)
          * [`obj spec.sideCars.volumes.projected.sources.serviceAccountToken`](#obj-specsidecarsvolumesprojectedsourcesserviceaccounttoken)
            * [`fn withAudience(audience)`](#fn-specsidecarsvolumesprojectedsourcesserviceaccounttokenwithaudience)
            * [`fn withExpirationSeconds(expirationSeconds)`](#fn-specsidecarsvolumesprojectedsourcesserviceaccounttokenwithexpirationseconds)
            * [`fn withPath(path)`](#fn-specsidecarsvolumesprojectedsourcesserviceaccounttokenwithpath)
      * [`obj spec.sideCars.volumes.quobyte`](#obj-specsidecarsvolumesquobyte)
        * [`fn withGroup(group)`](#fn-specsidecarsvolumesquobytewithgroup)
        * [`fn withReadOnly(readOnly)`](#fn-specsidecarsvolumesquobytewithreadonly)
        * [`fn withRegistry(registry)`](#fn-specsidecarsvolumesquobytewithregistry)
        * [`fn withTenant(tenant)`](#fn-specsidecarsvolumesquobytewithtenant)
        * [`fn withUser(user)`](#fn-specsidecarsvolumesquobytewithuser)
        * [`fn withVolume(volume)`](#fn-specsidecarsvolumesquobytewithvolume)
      * [`obj spec.sideCars.volumes.rbd`](#obj-specsidecarsvolumesrbd)
        * [`fn withFsType(fsType)`](#fn-specsidecarsvolumesrbdwithfstype)
        * [`fn withImage(image)`](#fn-specsidecarsvolumesrbdwithimage)
        * [`fn withKeyring(keyring)`](#fn-specsidecarsvolumesrbdwithkeyring)
        * [`fn withMonitors(monitors)`](#fn-specsidecarsvolumesrbdwithmonitors)
        * [`fn withMonitorsMixin(monitors)`](#fn-specsidecarsvolumesrbdwithmonitorsmixin)
        * [`fn withPool(pool)`](#fn-specsidecarsvolumesrbdwithpool)
        * [`fn withReadOnly(readOnly)`](#fn-specsidecarsvolumesrbdwithreadonly)
        * [`fn withUser(user)`](#fn-specsidecarsvolumesrbdwithuser)
        * [`obj spec.sideCars.volumes.rbd.secretRef`](#obj-specsidecarsvolumesrbdsecretref)
          * [`fn withName(name)`](#fn-specsidecarsvolumesrbdsecretrefwithname)
      * [`obj spec.sideCars.volumes.scaleIO`](#obj-specsidecarsvolumesscaleio)
        * [`fn withFsType(fsType)`](#fn-specsidecarsvolumesscaleiowithfstype)
        * [`fn withGateway(gateway)`](#fn-specsidecarsvolumesscaleiowithgateway)
        * [`fn withProtectionDomain(protectionDomain)`](#fn-specsidecarsvolumesscaleiowithprotectiondomain)
        * [`fn withReadOnly(readOnly)`](#fn-specsidecarsvolumesscaleiowithreadonly)
        * [`fn withSslEnabled(sslEnabled)`](#fn-specsidecarsvolumesscaleiowithsslenabled)
        * [`fn withStorageMode(storageMode)`](#fn-specsidecarsvolumesscaleiowithstoragemode)
        * [`fn withStoragePool(storagePool)`](#fn-specsidecarsvolumesscaleiowithstoragepool)
        * [`fn withSystem(system)`](#fn-specsidecarsvolumesscaleiowithsystem)
        * [`fn withVolumeName(volumeName)`](#fn-specsidecarsvolumesscaleiowithvolumename)
        * [`obj spec.sideCars.volumes.scaleIO.secretRef`](#obj-specsidecarsvolumesscaleiosecretref)
          * [`fn withName(name)`](#fn-specsidecarsvolumesscaleiosecretrefwithname)
      * [`obj spec.sideCars.volumes.secret`](#obj-specsidecarsvolumessecret)
        * [`fn withDefaultMode(defaultMode)`](#fn-specsidecarsvolumessecretwithdefaultmode)
        * [`fn withItems(items)`](#fn-specsidecarsvolumessecretwithitems)
        * [`fn withItemsMixin(items)`](#fn-specsidecarsvolumessecretwithitemsmixin)
        * [`fn withOptional(optional)`](#fn-specsidecarsvolumessecretwithoptional)
        * [`fn withSecretName(secretName)`](#fn-specsidecarsvolumessecretwithsecretname)
        * [`obj spec.sideCars.volumes.secret.items`](#obj-specsidecarsvolumessecretitems)
          * [`fn withKey(key)`](#fn-specsidecarsvolumessecretitemswithkey)
          * [`fn withMode(mode)`](#fn-specsidecarsvolumessecretitemswithmode)
          * [`fn withPath(path)`](#fn-specsidecarsvolumessecretitemswithpath)
      * [`obj spec.sideCars.volumes.storageos`](#obj-specsidecarsvolumesstorageos)
        * [`fn withFsType(fsType)`](#fn-specsidecarsvolumesstorageoswithfstype)
        * [`fn withReadOnly(readOnly)`](#fn-specsidecarsvolumesstorageoswithreadonly)
        * [`fn withVolumeName(volumeName)`](#fn-specsidecarsvolumesstorageoswithvolumename)
        * [`fn withVolumeNamespace(volumeNamespace)`](#fn-specsidecarsvolumesstorageoswithvolumenamespace)
        * [`obj spec.sideCars.volumes.storageos.secretRef`](#obj-specsidecarsvolumesstorageossecretref)
          * [`fn withName(name)`](#fn-specsidecarsvolumesstorageossecretrefwithname)
      * [`obj spec.sideCars.volumes.vsphereVolume`](#obj-specsidecarsvolumesvspherevolume)
        * [`fn withFsType(fsType)`](#fn-specsidecarsvolumesvspherevolumewithfstype)
        * [`fn withStoragePolicyID(storagePolicyID)`](#fn-specsidecarsvolumesvspherevolumewithstoragepolicyid)
        * [`fn withStoragePolicyName(storagePolicyName)`](#fn-specsidecarsvolumesvspherevolumewithstoragepolicyname)
        * [`fn withVolumePath(volumePath)`](#fn-specsidecarsvolumesvspherevolumewithvolumepath)
  * [`obj spec.startup`](#obj-specstartup)
    * [`fn withFailureThreshold(failureThreshold)`](#fn-specstartupwithfailurethreshold)
    * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specstartupwithinitialdelayseconds)
    * [`fn withPeriodSeconds(periodSeconds)`](#fn-specstartupwithperiodseconds)
    * [`fn withSuccessThreshold(successThreshold)`](#fn-specstartupwithsuccessthreshold)
    * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specstartupwithterminationgraceperiodseconds)
    * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specstartupwithtimeoutseconds)
    * [`obj spec.startup.exec`](#obj-specstartupexec)
      * [`fn withCommand(command)`](#fn-specstartupexecwithcommand)
      * [`fn withCommandMixin(command)`](#fn-specstartupexecwithcommandmixin)
    * [`obj spec.startup.grpc`](#obj-specstartupgrpc)
      * [`fn withPort(port)`](#fn-specstartupgrpcwithport)
      * [`fn withService(service)`](#fn-specstartupgrpcwithservice)
    * [`obj spec.startup.httpGet`](#obj-specstartuphttpget)
      * [`fn withHost(host)`](#fn-specstartuphttpgetwithhost)
      * [`fn withHttpHeaders(httpHeaders)`](#fn-specstartuphttpgetwithhttpheaders)
      * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specstartuphttpgetwithhttpheadersmixin)
      * [`fn withPath(path)`](#fn-specstartuphttpgetwithpath)
      * [`fn withPort(port)`](#fn-specstartuphttpgetwithport)
      * [`fn withScheme(scheme)`](#fn-specstartuphttpgetwithscheme)
      * [`obj spec.startup.httpGet.httpHeaders`](#obj-specstartuphttpgethttpheaders)
        * [`fn withName(name)`](#fn-specstartuphttpgethttpheaderswithname)
        * [`fn withValue(value)`](#fn-specstartuphttpgethttpheaderswithvalue)
    * [`obj spec.startup.tcpSocket`](#obj-specstartuptcpsocket)
      * [`fn withHost(host)`](#fn-specstartuptcpsocketwithhost)
      * [`fn withPort(port)`](#fn-specstartuptcpsocketwithport)
  * [`obj spec.users`](#obj-specusers)
    * [`fn withName(name)`](#fn-specuserswithname)

## Fields

### fn new

```ts
new(name)
```

new returns an instance of Tenant

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

## obj scheduler



### fn scheduler.withName

```ts
withName(name)
```



## obj spec



### fn spec.withAdditionalVolumeMounts

```ts
withAdditionalVolumeMounts(additionalVolumeMounts)
```



### fn spec.withAdditionalVolumeMountsMixin

```ts
withAdditionalVolumeMountsMixin(additionalVolumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.withAdditionalVolumes

```ts
withAdditionalVolumes(additionalVolumes)
```



### fn spec.withAdditionalVolumesMixin

```ts
withAdditionalVolumesMixin(additionalVolumes)
```



**Note:** This function appends passed data to existing values

### fn spec.withBuckets

```ts
withBuckets(buckets)
```



### fn spec.withBucketsMixin

```ts
withBucketsMixin(buckets)
```



**Note:** This function appends passed data to existing values

### fn spec.withEnv

```ts
withEnv(env)
```



### fn spec.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.withExternalCaCertSecret

```ts
withExternalCaCertSecret(externalCaCertSecret)
```



### fn spec.withExternalCaCertSecretMixin

```ts
withExternalCaCertSecretMixin(externalCaCertSecret)
```



**Note:** This function appends passed data to existing values

### fn spec.withExternalCertSecret

```ts
withExternalCertSecret(externalCertSecret)
```



### fn spec.withExternalCertSecretMixin

```ts
withExternalCertSecretMixin(externalCertSecret)
```



**Note:** This function appends passed data to existing values

### fn spec.withExternalClientCertSecrets

```ts
withExternalClientCertSecrets(externalClientCertSecrets)
```



### fn spec.withExternalClientCertSecretsMixin

```ts
withExternalClientCertSecretsMixin(externalClientCertSecrets)
```



**Note:** This function appends passed data to existing values

### fn spec.withImage

```ts
withImage(image)
```



### fn spec.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.withInitContainers

```ts
withInitContainers(initContainers)
```



### fn spec.withInitContainersMixin

```ts
withInitContainersMixin(initContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.withPodManagementPolicy

```ts
withPodManagementPolicy(podManagementPolicy)
```



### fn spec.withPools

```ts
withPools(pools)
```



### fn spec.withPoolsMixin

```ts
withPoolsMixin(pools)
```



**Note:** This function appends passed data to existing values

### fn spec.withPriorityClassName

```ts
withPriorityClassName(priorityClassName)
```



### fn spec.withPrometheusOperator

```ts
withPrometheusOperator(prometheusOperator)
```



### fn spec.withRequestAutoCert

```ts
withRequestAutoCert(requestAutoCert)
```



### fn spec.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.withUsers

```ts
withUsers(users)
```



### fn spec.withUsersMixin

```ts
withUsersMixin(users)
```



**Note:** This function appends passed data to existing values

## obj spec.additionalVolumeMounts



### fn spec.additionalVolumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.additionalVolumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.additionalVolumeMounts.withName

```ts
withName(name)
```



### fn spec.additionalVolumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.additionalVolumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.additionalVolumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.additionalVolumes



### fn spec.additionalVolumes.withName

```ts
withName(name)
```



## obj spec.additionalVolumes.awsElasticBlockStore



### fn spec.additionalVolumes.awsElasticBlockStore.withFsType

```ts
withFsType(fsType)
```



### fn spec.additionalVolumes.awsElasticBlockStore.withPartition

```ts
withPartition(partition)
```



### fn spec.additionalVolumes.awsElasticBlockStore.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.additionalVolumes.awsElasticBlockStore.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.additionalVolumes.azureDisk



### fn spec.additionalVolumes.azureDisk.withCachingMode

```ts
withCachingMode(cachingMode)
```



### fn spec.additionalVolumes.azureDisk.withDiskName

```ts
withDiskName(diskName)
```



### fn spec.additionalVolumes.azureDisk.withDiskURI

```ts
withDiskURI(diskURI)
```



### fn spec.additionalVolumes.azureDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.additionalVolumes.azureDisk.withKind

```ts
withKind(kind)
```



### fn spec.additionalVolumes.azureDisk.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.additionalVolumes.azureFile



### fn spec.additionalVolumes.azureFile.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.additionalVolumes.azureFile.withSecretName

```ts
withSecretName(secretName)
```



### fn spec.additionalVolumes.azureFile.withShareName

```ts
withShareName(shareName)
```



## obj spec.additionalVolumes.cephfs



### fn spec.additionalVolumes.cephfs.withMonitors

```ts
withMonitors(monitors)
```



### fn spec.additionalVolumes.cephfs.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```



**Note:** This function appends passed data to existing values

### fn spec.additionalVolumes.cephfs.withPath

```ts
withPath(path)
```



### fn spec.additionalVolumes.cephfs.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.additionalVolumes.cephfs.withSecretFile

```ts
withSecretFile(secretFile)
```



### fn spec.additionalVolumes.cephfs.withUser

```ts
withUser(user)
```



## obj spec.additionalVolumes.cephfs.secretRef



### fn spec.additionalVolumes.cephfs.secretRef.withName

```ts
withName(name)
```



## obj spec.additionalVolumes.cinder



### fn spec.additionalVolumes.cinder.withFsType

```ts
withFsType(fsType)
```



### fn spec.additionalVolumes.cinder.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.additionalVolumes.cinder.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.additionalVolumes.cinder.secretRef



### fn spec.additionalVolumes.cinder.secretRef.withName

```ts
withName(name)
```



## obj spec.additionalVolumes.configMap



### fn spec.additionalVolumes.configMap.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.additionalVolumes.configMap.withItems

```ts
withItems(items)
```



### fn spec.additionalVolumes.configMap.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.additionalVolumes.configMap.withName

```ts
withName(name)
```



### fn spec.additionalVolumes.configMap.withOptional

```ts
withOptional(optional)
```



## obj spec.additionalVolumes.configMap.items



### fn spec.additionalVolumes.configMap.items.withKey

```ts
withKey(key)
```



### fn spec.additionalVolumes.configMap.items.withMode

```ts
withMode(mode)
```



### fn spec.additionalVolumes.configMap.items.withPath

```ts
withPath(path)
```



## obj spec.additionalVolumes.csi



### fn spec.additionalVolumes.csi.withDriver

```ts
withDriver(driver)
```



### fn spec.additionalVolumes.csi.withFsType

```ts
withFsType(fsType)
```



### fn spec.additionalVolumes.csi.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.additionalVolumes.csi.withVolumeAttributes

```ts
withVolumeAttributes(volumeAttributes)
```



### fn spec.additionalVolumes.csi.withVolumeAttributesMixin

```ts
withVolumeAttributesMixin(volumeAttributes)
```



**Note:** This function appends passed data to existing values

## obj spec.additionalVolumes.csi.nodePublishSecretRef



### fn spec.additionalVolumes.csi.nodePublishSecretRef.withName

```ts
withName(name)
```



## obj spec.additionalVolumes.downwardAPI



### fn spec.additionalVolumes.downwardAPI.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.additionalVolumes.downwardAPI.withItems

```ts
withItems(items)
```



### fn spec.additionalVolumes.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

## obj spec.additionalVolumes.downwardAPI.items



### fn spec.additionalVolumes.downwardAPI.items.withMode

```ts
withMode(mode)
```



### fn spec.additionalVolumes.downwardAPI.items.withPath

```ts
withPath(path)
```



## obj spec.additionalVolumes.downwardAPI.items.fieldRef



### fn spec.additionalVolumes.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.additionalVolumes.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.additionalVolumes.downwardAPI.items.resourceFieldRef



### fn spec.additionalVolumes.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.additionalVolumes.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.additionalVolumes.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.additionalVolumes.emptyDir



### fn spec.additionalVolumes.emptyDir.withMedium

```ts
withMedium(medium)
```



### fn spec.additionalVolumes.emptyDir.withSizeLimit

```ts
withSizeLimit(sizeLimit)
```



## obj spec.additionalVolumes.ephemeral



## obj spec.additionalVolumes.ephemeral.volumeClaimTemplate



## obj spec.additionalVolumes.ephemeral.volumeClaimTemplate.metadata



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.metadata.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.metadata.withFinalizers

```ts
withFinalizers(finalizers)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.metadata.withFinalizersMixin

```ts
withFinalizersMixin(finalizers)
```



**Note:** This function appends passed data to existing values

### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.metadata.withLabels

```ts
withLabels(labels)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.metadata.withName

```ts
withName(name)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.metadata.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.withAccessModes

```ts
withAccessModes(accessModes)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.withAccessModesMixin

```ts
withAccessModesMixin(accessModes)
```



**Note:** This function appends passed data to existing values

### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.withStorageClassName

```ts
withStorageClassName(storageClassName)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.withVolumeAttributesClassName

```ts
withVolumeAttributesClassName(volumeAttributesClassName)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.withVolumeMode

```ts
withVolumeMode(volumeMode)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.dataSource



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.dataSource.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.dataSource.withKind

```ts
withKind(kind)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.dataSource.withName

```ts
withName(name)
```



## obj spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withKind

```ts
withKind(kind)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withName

```ts
withName(name)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.resources



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.selector



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.additionalVolumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.additionalVolumes.fc



### fn spec.additionalVolumes.fc.withFsType

```ts
withFsType(fsType)
```



### fn spec.additionalVolumes.fc.withLun

```ts
withLun(lun)
```



### fn spec.additionalVolumes.fc.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.additionalVolumes.fc.withTargetWWNs

```ts
withTargetWWNs(targetWWNs)
```



### fn spec.additionalVolumes.fc.withTargetWWNsMixin

```ts
withTargetWWNsMixin(targetWWNs)
```



**Note:** This function appends passed data to existing values

### fn spec.additionalVolumes.fc.withWwids

```ts
withWwids(wwids)
```



### fn spec.additionalVolumes.fc.withWwidsMixin

```ts
withWwidsMixin(wwids)
```



**Note:** This function appends passed data to existing values

## obj spec.additionalVolumes.flexVolume



### fn spec.additionalVolumes.flexVolume.withDriver

```ts
withDriver(driver)
```



### fn spec.additionalVolumes.flexVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.additionalVolumes.flexVolume.withOptions

```ts
withOptions(options)
```



### fn spec.additionalVolumes.flexVolume.withOptionsMixin

```ts
withOptionsMixin(options)
```



**Note:** This function appends passed data to existing values

### fn spec.additionalVolumes.flexVolume.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.additionalVolumes.flexVolume.secretRef



### fn spec.additionalVolumes.flexVolume.secretRef.withName

```ts
withName(name)
```



## obj spec.additionalVolumes.flocker



### fn spec.additionalVolumes.flocker.withDatasetName

```ts
withDatasetName(datasetName)
```



### fn spec.additionalVolumes.flocker.withDatasetUUID

```ts
withDatasetUUID(datasetUUID)
```



## obj spec.additionalVolumes.gcePersistentDisk



### fn spec.additionalVolumes.gcePersistentDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.additionalVolumes.gcePersistentDisk.withPartition

```ts
withPartition(partition)
```



### fn spec.additionalVolumes.gcePersistentDisk.withPdName

```ts
withPdName(pdName)
```



### fn spec.additionalVolumes.gcePersistentDisk.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.additionalVolumes.gitRepo



### fn spec.additionalVolumes.gitRepo.withDirectory

```ts
withDirectory(directory)
```



### fn spec.additionalVolumes.gitRepo.withRepository

```ts
withRepository(repository)
```



### fn spec.additionalVolumes.gitRepo.withRevision

```ts
withRevision(revision)
```



## obj spec.additionalVolumes.glusterfs



### fn spec.additionalVolumes.glusterfs.withEndpoints

```ts
withEndpoints(endpoints)
```



### fn spec.additionalVolumes.glusterfs.withPath

```ts
withPath(path)
```



### fn spec.additionalVolumes.glusterfs.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.additionalVolumes.hostPath



### fn spec.additionalVolumes.hostPath.withPath

```ts
withPath(path)
```



### fn spec.additionalVolumes.hostPath.withType

```ts
withType(type)
```



## obj spec.additionalVolumes.iscsi



### fn spec.additionalVolumes.iscsi.withChapAuthDiscovery

```ts
withChapAuthDiscovery(chapAuthDiscovery)
```



### fn spec.additionalVolumes.iscsi.withChapAuthSession

```ts
withChapAuthSession(chapAuthSession)
```



### fn spec.additionalVolumes.iscsi.withFsType

```ts
withFsType(fsType)
```



### fn spec.additionalVolumes.iscsi.withInitiatorName

```ts
withInitiatorName(initiatorName)
```



### fn spec.additionalVolumes.iscsi.withIqn

```ts
withIqn(iqn)
```



### fn spec.additionalVolumes.iscsi.withIscsiInterface

```ts
withIscsiInterface(iscsiInterface)
```



### fn spec.additionalVolumes.iscsi.withLun

```ts
withLun(lun)
```



### fn spec.additionalVolumes.iscsi.withPortals

```ts
withPortals(portals)
```



### fn spec.additionalVolumes.iscsi.withPortalsMixin

```ts
withPortalsMixin(portals)
```



**Note:** This function appends passed data to existing values

### fn spec.additionalVolumes.iscsi.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.additionalVolumes.iscsi.withTargetPortal

```ts
withTargetPortal(targetPortal)
```



## obj spec.additionalVolumes.iscsi.secretRef



### fn spec.additionalVolumes.iscsi.secretRef.withName

```ts
withName(name)
```



## obj spec.additionalVolumes.nfs



### fn spec.additionalVolumes.nfs.withPath

```ts
withPath(path)
```



### fn spec.additionalVolumes.nfs.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.additionalVolumes.nfs.withServer

```ts
withServer(server)
```



## obj spec.additionalVolumes.persistentVolumeClaim



### fn spec.additionalVolumes.persistentVolumeClaim.withClaimName

```ts
withClaimName(claimName)
```



### fn spec.additionalVolumes.persistentVolumeClaim.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.additionalVolumes.photonPersistentDisk



### fn spec.additionalVolumes.photonPersistentDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.additionalVolumes.photonPersistentDisk.withPdID

```ts
withPdID(pdID)
```



## obj spec.additionalVolumes.portworxVolume



### fn spec.additionalVolumes.portworxVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.additionalVolumes.portworxVolume.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.additionalVolumes.portworxVolume.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.additionalVolumes.projected



### fn spec.additionalVolumes.projected.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.additionalVolumes.projected.withSources

```ts
withSources(sources)
```



### fn spec.additionalVolumes.projected.withSourcesMixin

```ts
withSourcesMixin(sources)
```



**Note:** This function appends passed data to existing values

## obj spec.additionalVolumes.projected.sources



## obj spec.additionalVolumes.projected.sources.clusterTrustBundle



### fn spec.additionalVolumes.projected.sources.clusterTrustBundle.withName

```ts
withName(name)
```



### fn spec.additionalVolumes.projected.sources.clusterTrustBundle.withOptional

```ts
withOptional(optional)
```



### fn spec.additionalVolumes.projected.sources.clusterTrustBundle.withPath

```ts
withPath(path)
```



### fn spec.additionalVolumes.projected.sources.clusterTrustBundle.withSignerName

```ts
withSignerName(signerName)
```



## obj spec.additionalVolumes.projected.sources.clusterTrustBundle.labelSelector



### fn spec.additionalVolumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.additionalVolumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.additionalVolumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.additionalVolumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.additionalVolumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions



### fn spec.additionalVolumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.additionalVolumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.additionalVolumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.additionalVolumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.additionalVolumes.projected.sources.configMap



### fn spec.additionalVolumes.projected.sources.configMap.withItems

```ts
withItems(items)
```



### fn spec.additionalVolumes.projected.sources.configMap.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.additionalVolumes.projected.sources.configMap.withName

```ts
withName(name)
```



### fn spec.additionalVolumes.projected.sources.configMap.withOptional

```ts
withOptional(optional)
```



## obj spec.additionalVolumes.projected.sources.configMap.items



### fn spec.additionalVolumes.projected.sources.configMap.items.withKey

```ts
withKey(key)
```



### fn spec.additionalVolumes.projected.sources.configMap.items.withMode

```ts
withMode(mode)
```



### fn spec.additionalVolumes.projected.sources.configMap.items.withPath

```ts
withPath(path)
```



## obj spec.additionalVolumes.projected.sources.downwardAPI



### fn spec.additionalVolumes.projected.sources.downwardAPI.withItems

```ts
withItems(items)
```



### fn spec.additionalVolumes.projected.sources.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

## obj spec.additionalVolumes.projected.sources.downwardAPI.items



### fn spec.additionalVolumes.projected.sources.downwardAPI.items.withMode

```ts
withMode(mode)
```



### fn spec.additionalVolumes.projected.sources.downwardAPI.items.withPath

```ts
withPath(path)
```



## obj spec.additionalVolumes.projected.sources.downwardAPI.items.fieldRef



### fn spec.additionalVolumes.projected.sources.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.additionalVolumes.projected.sources.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.additionalVolumes.projected.sources.downwardAPI.items.resourceFieldRef



### fn spec.additionalVolumes.projected.sources.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.additionalVolumes.projected.sources.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.additionalVolumes.projected.sources.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.additionalVolumes.projected.sources.secret



### fn spec.additionalVolumes.projected.sources.secret.withItems

```ts
withItems(items)
```



### fn spec.additionalVolumes.projected.sources.secret.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.additionalVolumes.projected.sources.secret.withName

```ts
withName(name)
```



### fn spec.additionalVolumes.projected.sources.secret.withOptional

```ts
withOptional(optional)
```



## obj spec.additionalVolumes.projected.sources.secret.items



### fn spec.additionalVolumes.projected.sources.secret.items.withKey

```ts
withKey(key)
```



### fn spec.additionalVolumes.projected.sources.secret.items.withMode

```ts
withMode(mode)
```



### fn spec.additionalVolumes.projected.sources.secret.items.withPath

```ts
withPath(path)
```



## obj spec.additionalVolumes.projected.sources.serviceAccountToken



### fn spec.additionalVolumes.projected.sources.serviceAccountToken.withAudience

```ts
withAudience(audience)
```



### fn spec.additionalVolumes.projected.sources.serviceAccountToken.withExpirationSeconds

```ts
withExpirationSeconds(expirationSeconds)
```



### fn spec.additionalVolumes.projected.sources.serviceAccountToken.withPath

```ts
withPath(path)
```



## obj spec.additionalVolumes.quobyte



### fn spec.additionalVolumes.quobyte.withGroup

```ts
withGroup(group)
```



### fn spec.additionalVolumes.quobyte.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.additionalVolumes.quobyte.withRegistry

```ts
withRegistry(registry)
```



### fn spec.additionalVolumes.quobyte.withTenant

```ts
withTenant(tenant)
```



### fn spec.additionalVolumes.quobyte.withUser

```ts
withUser(user)
```



### fn spec.additionalVolumes.quobyte.withVolume

```ts
withVolume(volume)
```



## obj spec.additionalVolumes.rbd



### fn spec.additionalVolumes.rbd.withFsType

```ts
withFsType(fsType)
```



### fn spec.additionalVolumes.rbd.withImage

```ts
withImage(image)
```



### fn spec.additionalVolumes.rbd.withKeyring

```ts
withKeyring(keyring)
```



### fn spec.additionalVolumes.rbd.withMonitors

```ts
withMonitors(monitors)
```



### fn spec.additionalVolumes.rbd.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```



**Note:** This function appends passed data to existing values

### fn spec.additionalVolumes.rbd.withPool

```ts
withPool(pool)
```



### fn spec.additionalVolumes.rbd.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.additionalVolumes.rbd.withUser

```ts
withUser(user)
```



## obj spec.additionalVolumes.rbd.secretRef



### fn spec.additionalVolumes.rbd.secretRef.withName

```ts
withName(name)
```



## obj spec.additionalVolumes.scaleIO



### fn spec.additionalVolumes.scaleIO.withFsType

```ts
withFsType(fsType)
```



### fn spec.additionalVolumes.scaleIO.withGateway

```ts
withGateway(gateway)
```



### fn spec.additionalVolumes.scaleIO.withProtectionDomain

```ts
withProtectionDomain(protectionDomain)
```



### fn spec.additionalVolumes.scaleIO.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.additionalVolumes.scaleIO.withSslEnabled

```ts
withSslEnabled(sslEnabled)
```



### fn spec.additionalVolumes.scaleIO.withStorageMode

```ts
withStorageMode(storageMode)
```



### fn spec.additionalVolumes.scaleIO.withStoragePool

```ts
withStoragePool(storagePool)
```



### fn spec.additionalVolumes.scaleIO.withSystem

```ts
withSystem(system)
```



### fn spec.additionalVolumes.scaleIO.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.additionalVolumes.scaleIO.secretRef



### fn spec.additionalVolumes.scaleIO.secretRef.withName

```ts
withName(name)
```



## obj spec.additionalVolumes.secret



### fn spec.additionalVolumes.secret.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.additionalVolumes.secret.withItems

```ts
withItems(items)
```



### fn spec.additionalVolumes.secret.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.additionalVolumes.secret.withOptional

```ts
withOptional(optional)
```



### fn spec.additionalVolumes.secret.withSecretName

```ts
withSecretName(secretName)
```



## obj spec.additionalVolumes.secret.items



### fn spec.additionalVolumes.secret.items.withKey

```ts
withKey(key)
```



### fn spec.additionalVolumes.secret.items.withMode

```ts
withMode(mode)
```



### fn spec.additionalVolumes.secret.items.withPath

```ts
withPath(path)
```



## obj spec.additionalVolumes.storageos



### fn spec.additionalVolumes.storageos.withFsType

```ts
withFsType(fsType)
```



### fn spec.additionalVolumes.storageos.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.additionalVolumes.storageos.withVolumeName

```ts
withVolumeName(volumeName)
```



### fn spec.additionalVolumes.storageos.withVolumeNamespace

```ts
withVolumeNamespace(volumeNamespace)
```



## obj spec.additionalVolumes.storageos.secretRef



### fn spec.additionalVolumes.storageos.secretRef.withName

```ts
withName(name)
```



## obj spec.additionalVolumes.vsphereVolume



### fn spec.additionalVolumes.vsphereVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.additionalVolumes.vsphereVolume.withStoragePolicyID

```ts
withStoragePolicyID(storagePolicyID)
```



### fn spec.additionalVolumes.vsphereVolume.withStoragePolicyName

```ts
withStoragePolicyName(storagePolicyName)
```



### fn spec.additionalVolumes.vsphereVolume.withVolumePath

```ts
withVolumePath(volumePath)
```



## obj spec.buckets



### fn spec.buckets.withName

```ts
withName(name)
```



### fn spec.buckets.withObjectLock

```ts
withObjectLock(objectLock)
```



### fn spec.buckets.withRegion

```ts
withRegion(region)
```



## obj spec.certConfig



### fn spec.certConfig.withCommonName

```ts
withCommonName(commonName)
```



### fn spec.certConfig.withDnsNames

```ts
withDnsNames(dnsNames)
```



### fn spec.certConfig.withDnsNamesMixin

```ts
withDnsNamesMixin(dnsNames)
```



**Note:** This function appends passed data to existing values

### fn spec.certConfig.withOrganizationName

```ts
withOrganizationName(organizationName)
```



### fn spec.certConfig.withOrganizationNameMixin

```ts
withOrganizationNameMixin(organizationName)
```



**Note:** This function appends passed data to existing values

## obj spec.configuration



### fn spec.configuration.withName

```ts
withName(name)
```



## obj spec.credsSecret



### fn spec.credsSecret.withName

```ts
withName(name)
```



## obj spec.env



### fn spec.env.withName

```ts
withName(name)
```



### fn spec.env.withValue

```ts
withValue(value)
```



## obj spec.env.valueFrom



## obj spec.env.valueFrom.configMapKeyRef



### fn spec.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.env.valueFrom.fieldRef



### fn spec.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.env.valueFrom.resourceFieldRef



### fn spec.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.env.valueFrom.secretKeyRef



### fn spec.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.exposeServices



### fn spec.exposeServices.withConsole

```ts
withConsole(console)
```



### fn spec.exposeServices.withMinio

```ts
withMinio(minio)
```



## obj spec.externalCaCertSecret



### fn spec.externalCaCertSecret.withName

```ts
withName(name)
```



### fn spec.externalCaCertSecret.withType

```ts
withType(type)
```



## obj spec.externalCertSecret



### fn spec.externalCertSecret.withName

```ts
withName(name)
```



### fn spec.externalCertSecret.withType

```ts
withType(type)
```



## obj spec.externalClientCertSecret



### fn spec.externalClientCertSecret.withName

```ts
withName(name)
```



### fn spec.externalClientCertSecret.withType

```ts
withType(type)
```



## obj spec.externalClientCertSecrets



### fn spec.externalClientCertSecrets.withName

```ts
withName(name)
```



### fn spec.externalClientCertSecrets.withType

```ts
withType(type)
```



## obj spec.features



### fn spec.features.withBucketDNS

```ts
withBucketDNS(bucketDNS)
```



### fn spec.features.withEnableSFTP

```ts
withEnableSFTP(enableSFTP)
```



## obj spec.features.domains



### fn spec.features.domains.withConsole

```ts
withConsole(console)
```



### fn spec.features.domains.withMinio

```ts
withMinio(minio)
```



### fn spec.features.domains.withMinioMixin

```ts
withMinioMixin(minio)
```



**Note:** This function appends passed data to existing values

## obj spec.imagePullSecret



### fn spec.imagePullSecret.withName

```ts
withName(name)
```



## obj spec.initContainers



### fn spec.initContainers.withArgs

```ts
withArgs(args)
```



### fn spec.initContainers.withArgsMixin

```ts
withArgsMixin(args)
```



**Note:** This function appends passed data to existing values

### fn spec.initContainers.withCommand

```ts
withCommand(command)
```



### fn spec.initContainers.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

### fn spec.initContainers.withEnv

```ts
withEnv(env)
```



### fn spec.initContainers.withEnvFrom

```ts
withEnvFrom(envFrom)
```



### fn spec.initContainers.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```



**Note:** This function appends passed data to existing values

### fn spec.initContainers.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.initContainers.withImage

```ts
withImage(image)
```



### fn spec.initContainers.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.initContainers.withName

```ts
withName(name)
```



### fn spec.initContainers.withPorts

```ts
withPorts(ports)
```



### fn spec.initContainers.withPortsMixin

```ts
withPortsMixin(ports)
```



**Note:** This function appends passed data to existing values

### fn spec.initContainers.withResizePolicy

```ts
withResizePolicy(resizePolicy)
```



### fn spec.initContainers.withResizePolicyMixin

```ts
withResizePolicyMixin(resizePolicy)
```



**Note:** This function appends passed data to existing values

### fn spec.initContainers.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



### fn spec.initContainers.withStdin

```ts
withStdin(stdin)
```



### fn spec.initContainers.withStdinOnce

```ts
withStdinOnce(stdinOnce)
```



### fn spec.initContainers.withTerminationMessagePath

```ts
withTerminationMessagePath(terminationMessagePath)
```



### fn spec.initContainers.withTerminationMessagePolicy

```ts
withTerminationMessagePolicy(terminationMessagePolicy)
```



### fn spec.initContainers.withTty

```ts
withTty(tty)
```



### fn spec.initContainers.withVolumeDevices

```ts
withVolumeDevices(volumeDevices)
```



### fn spec.initContainers.withVolumeDevicesMixin

```ts
withVolumeDevicesMixin(volumeDevices)
```



**Note:** This function appends passed data to existing values

### fn spec.initContainers.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.initContainers.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.initContainers.withWorkingDir

```ts
withWorkingDir(workingDir)
```



## obj spec.initContainers.env



### fn spec.initContainers.env.withName

```ts
withName(name)
```



### fn spec.initContainers.env.withValue

```ts
withValue(value)
```



## obj spec.initContainers.env.valueFrom



## obj spec.initContainers.env.valueFrom.configMapKeyRef



### fn spec.initContainers.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.initContainers.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.initContainers.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.initContainers.env.valueFrom.fieldRef



### fn spec.initContainers.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.initContainers.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.initContainers.env.valueFrom.resourceFieldRef



### fn spec.initContainers.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.initContainers.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.initContainers.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.initContainers.env.valueFrom.secretKeyRef



### fn spec.initContainers.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.initContainers.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.initContainers.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.initContainers.envFrom



### fn spec.initContainers.envFrom.withPrefix

```ts
withPrefix(prefix)
```



## obj spec.initContainers.envFrom.configMapRef



### fn spec.initContainers.envFrom.configMapRef.withName

```ts
withName(name)
```



### fn spec.initContainers.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```



## obj spec.initContainers.envFrom.secretRef



### fn spec.initContainers.envFrom.secretRef.withName

```ts
withName(name)
```



### fn spec.initContainers.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```



## obj spec.initContainers.lifecycle



## obj spec.initContainers.lifecycle.postStart



## obj spec.initContainers.lifecycle.postStart.exec



### fn spec.initContainers.lifecycle.postStart.exec.withCommand

```ts
withCommand(command)
```



### fn spec.initContainers.lifecycle.postStart.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.initContainers.lifecycle.postStart.httpGet



### fn spec.initContainers.lifecycle.postStart.httpGet.withHost

```ts
withHost(host)
```



### fn spec.initContainers.lifecycle.postStart.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.initContainers.lifecycle.postStart.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.initContainers.lifecycle.postStart.httpGet.withPath

```ts
withPath(path)
```



### fn spec.initContainers.lifecycle.postStart.httpGet.withPort

```ts
withPort(port)
```



### fn spec.initContainers.lifecycle.postStart.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.initContainers.lifecycle.postStart.httpGet.httpHeaders



### fn spec.initContainers.lifecycle.postStart.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.initContainers.lifecycle.postStart.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.initContainers.lifecycle.postStart.sleep



### fn spec.initContainers.lifecycle.postStart.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.initContainers.lifecycle.postStart.tcpSocket



### fn spec.initContainers.lifecycle.postStart.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.initContainers.lifecycle.postStart.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.initContainers.lifecycle.preStop



## obj spec.initContainers.lifecycle.preStop.exec



### fn spec.initContainers.lifecycle.preStop.exec.withCommand

```ts
withCommand(command)
```



### fn spec.initContainers.lifecycle.preStop.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.initContainers.lifecycle.preStop.httpGet



### fn spec.initContainers.lifecycle.preStop.httpGet.withHost

```ts
withHost(host)
```



### fn spec.initContainers.lifecycle.preStop.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.initContainers.lifecycle.preStop.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.initContainers.lifecycle.preStop.httpGet.withPath

```ts
withPath(path)
```



### fn spec.initContainers.lifecycle.preStop.httpGet.withPort

```ts
withPort(port)
```



### fn spec.initContainers.lifecycle.preStop.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.initContainers.lifecycle.preStop.httpGet.httpHeaders



### fn spec.initContainers.lifecycle.preStop.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.initContainers.lifecycle.preStop.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.initContainers.lifecycle.preStop.sleep



### fn spec.initContainers.lifecycle.preStop.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.initContainers.lifecycle.preStop.tcpSocket



### fn spec.initContainers.lifecycle.preStop.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.initContainers.lifecycle.preStop.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.initContainers.livenessProbe



### fn spec.initContainers.livenessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.initContainers.livenessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.initContainers.livenessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.initContainers.livenessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.initContainers.livenessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.initContainers.livenessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.initContainers.livenessProbe.exec



### fn spec.initContainers.livenessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.initContainers.livenessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.initContainers.livenessProbe.grpc



### fn spec.initContainers.livenessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.initContainers.livenessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.initContainers.livenessProbe.httpGet



### fn spec.initContainers.livenessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.initContainers.livenessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.initContainers.livenessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.initContainers.livenessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.initContainers.livenessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.initContainers.livenessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.initContainers.livenessProbe.httpGet.httpHeaders



### fn spec.initContainers.livenessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.initContainers.livenessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.initContainers.livenessProbe.tcpSocket



### fn spec.initContainers.livenessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.initContainers.livenessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.initContainers.ports



### fn spec.initContainers.ports.withContainerPort

```ts
withContainerPort(containerPort)
```



### fn spec.initContainers.ports.withHostIP

```ts
withHostIP(hostIP)
```



### fn spec.initContainers.ports.withHostPort

```ts
withHostPort(hostPort)
```



### fn spec.initContainers.ports.withName

```ts
withName(name)
```



### fn spec.initContainers.ports.withProtocol

```ts
withProtocol(protocol)
```



## obj spec.initContainers.readinessProbe



### fn spec.initContainers.readinessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.initContainers.readinessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.initContainers.readinessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.initContainers.readinessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.initContainers.readinessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.initContainers.readinessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.initContainers.readinessProbe.exec



### fn spec.initContainers.readinessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.initContainers.readinessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.initContainers.readinessProbe.grpc



### fn spec.initContainers.readinessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.initContainers.readinessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.initContainers.readinessProbe.httpGet



### fn spec.initContainers.readinessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.initContainers.readinessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.initContainers.readinessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.initContainers.readinessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.initContainers.readinessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.initContainers.readinessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.initContainers.readinessProbe.httpGet.httpHeaders



### fn spec.initContainers.readinessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.initContainers.readinessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.initContainers.readinessProbe.tcpSocket



### fn spec.initContainers.readinessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.initContainers.readinessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.initContainers.resizePolicy



### fn spec.initContainers.resizePolicy.withResourceName

```ts
withResourceName(resourceName)
```



### fn spec.initContainers.resizePolicy.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



## obj spec.initContainers.resources



### fn spec.initContainers.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.initContainers.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.initContainers.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.initContainers.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.initContainers.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.initContainers.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.initContainers.resources.claims



### fn spec.initContainers.resources.claims.withName

```ts
withName(name)
```



## obj spec.initContainers.securityContext



### fn spec.initContainers.securityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```



### fn spec.initContainers.securityContext.withPrivileged

```ts
withPrivileged(privileged)
```



### fn spec.initContainers.securityContext.withProcMount

```ts
withProcMount(procMount)
```



### fn spec.initContainers.securityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```



### fn spec.initContainers.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.initContainers.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.initContainers.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



## obj spec.initContainers.securityContext.capabilities



### fn spec.initContainers.securityContext.capabilities.withAdd

```ts
withAdd(add)
```



### fn spec.initContainers.securityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```



**Note:** This function appends passed data to existing values

### fn spec.initContainers.securityContext.capabilities.withDrop

```ts
withDrop(drop)
```



### fn spec.initContainers.securityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```



**Note:** This function appends passed data to existing values

## obj spec.initContainers.securityContext.seLinuxOptions



### fn spec.initContainers.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.initContainers.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.initContainers.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.initContainers.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.initContainers.securityContext.seccompProfile



### fn spec.initContainers.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.initContainers.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.initContainers.securityContext.windowsOptions



### fn spec.initContainers.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.initContainers.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.initContainers.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.initContainers.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.initContainers.startupProbe



### fn spec.initContainers.startupProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.initContainers.startupProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.initContainers.startupProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.initContainers.startupProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.initContainers.startupProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.initContainers.startupProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.initContainers.startupProbe.exec



### fn spec.initContainers.startupProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.initContainers.startupProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.initContainers.startupProbe.grpc



### fn spec.initContainers.startupProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.initContainers.startupProbe.grpc.withService

```ts
withService(service)
```



## obj spec.initContainers.startupProbe.httpGet



### fn spec.initContainers.startupProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.initContainers.startupProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.initContainers.startupProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.initContainers.startupProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.initContainers.startupProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.initContainers.startupProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.initContainers.startupProbe.httpGet.httpHeaders



### fn spec.initContainers.startupProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.initContainers.startupProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.initContainers.startupProbe.tcpSocket



### fn spec.initContainers.startupProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.initContainers.startupProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.initContainers.volumeDevices



### fn spec.initContainers.volumeDevices.withDevicePath

```ts
withDevicePath(devicePath)
```



### fn spec.initContainers.volumeDevices.withName

```ts
withName(name)
```



## obj spec.initContainers.volumeMounts



### fn spec.initContainers.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.initContainers.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.initContainers.volumeMounts.withName

```ts
withName(name)
```



### fn spec.initContainers.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.initContainers.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.initContainers.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.kes



### fn spec.kes.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.kes.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.withEnv

```ts
withEnv(env)
```



### fn spec.kes.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.withGcpCredentialSecretName

```ts
withGcpCredentialSecretName(gcpCredentialSecretName)
```



### fn spec.kes.withGcpWorkloadIdentityPool

```ts
withGcpWorkloadIdentityPool(gcpWorkloadIdentityPool)
```



### fn spec.kes.withImage

```ts
withImage(image)
```



### fn spec.kes.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.kes.withKeyName

```ts
withKeyName(keyName)
```



### fn spec.kes.withLabels

```ts
withLabels(labels)
```



### fn spec.kes.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.kes.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.withReplicas

```ts
withReplicas(replicas)
```



### fn spec.kes.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.kes.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.kes.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.withTopologySpreadConstraints

```ts
withTopologySpreadConstraints(topologySpreadConstraints)
```



### fn spec.kes.withTopologySpreadConstraintsMixin

```ts
withTopologySpreadConstraintsMixin(topologySpreadConstraints)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity



## obj spec.kes.affinity.nodeAffinity



### fn spec.kes.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.kes.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.kes.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.kes.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.podAffinity



### fn spec.kes.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.kes.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.kes.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.kes.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.kes.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.podAntiAffinity



### fn spec.kes.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.kes.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.kes.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.kes.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.kes.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.clientCertSecret



### fn spec.kes.clientCertSecret.withName

```ts
withName(name)
```



### fn spec.kes.clientCertSecret.withType

```ts
withType(type)
```



## obj spec.kes.containerSecurityContext



### fn spec.kes.containerSecurityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```



### fn spec.kes.containerSecurityContext.withPrivileged

```ts
withPrivileged(privileged)
```



### fn spec.kes.containerSecurityContext.withProcMount

```ts
withProcMount(procMount)
```



### fn spec.kes.containerSecurityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```



### fn spec.kes.containerSecurityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.kes.containerSecurityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.kes.containerSecurityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



## obj spec.kes.containerSecurityContext.capabilities



### fn spec.kes.containerSecurityContext.capabilities.withAdd

```ts
withAdd(add)
```



### fn spec.kes.containerSecurityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.containerSecurityContext.capabilities.withDrop

```ts
withDrop(drop)
```



### fn spec.kes.containerSecurityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.containerSecurityContext.seLinuxOptions



### fn spec.kes.containerSecurityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.kes.containerSecurityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.kes.containerSecurityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.kes.containerSecurityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.kes.containerSecurityContext.seccompProfile



### fn spec.kes.containerSecurityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.kes.containerSecurityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.kes.containerSecurityContext.windowsOptions



### fn spec.kes.containerSecurityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.kes.containerSecurityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.kes.containerSecurityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.kes.containerSecurityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.kes.env



### fn spec.kes.env.withName

```ts
withName(name)
```



### fn spec.kes.env.withValue

```ts
withValue(value)
```



## obj spec.kes.env.valueFrom



## obj spec.kes.env.valueFrom.configMapKeyRef



### fn spec.kes.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.kes.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.kes.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.kes.env.valueFrom.fieldRef



### fn spec.kes.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.kes.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.kes.env.valueFrom.resourceFieldRef



### fn spec.kes.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.kes.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.kes.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.kes.env.valueFrom.secretKeyRef



### fn spec.kes.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.kes.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.kes.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.kes.externalCertSecret



### fn spec.kes.externalCertSecret.withName

```ts
withName(name)
```



### fn spec.kes.externalCertSecret.withType

```ts
withType(type)
```



## obj spec.kes.kesSecret



### fn spec.kes.kesSecret.withName

```ts
withName(name)
```



## obj spec.kes.resources



### fn spec.kes.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.kes.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.kes.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.kes.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.resources.claims



### fn spec.kes.resources.claims.withName

```ts
withName(name)
```



## obj spec.kes.securityContext



### fn spec.kes.securityContext.withFsGroup

```ts
withFsGroup(fsGroup)
```



### fn spec.kes.securityContext.withFsGroupChangePolicy

```ts
withFsGroupChangePolicy(fsGroupChangePolicy)
```



### fn spec.kes.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.kes.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.kes.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



### fn spec.kes.securityContext.withSupplementalGroups

```ts
withSupplementalGroups(supplementalGroups)
```



### fn spec.kes.securityContext.withSupplementalGroupsMixin

```ts
withSupplementalGroupsMixin(supplementalGroups)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.securityContext.withSysctls

```ts
withSysctls(sysctls)
```



### fn spec.kes.securityContext.withSysctlsMixin

```ts
withSysctlsMixin(sysctls)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.securityContext.seLinuxOptions



### fn spec.kes.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.kes.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.kes.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.kes.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.kes.securityContext.seccompProfile



### fn spec.kes.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.kes.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.kes.securityContext.sysctls



### fn spec.kes.securityContext.sysctls.withName

```ts
withName(name)
```



### fn spec.kes.securityContext.sysctls.withValue

```ts
withValue(value)
```



## obj spec.kes.securityContext.windowsOptions



### fn spec.kes.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.kes.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.kes.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.kes.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.kes.tolerations



### fn spec.kes.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.kes.tolerations.withKey

```ts
withKey(key)
```



### fn spec.kes.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.kes.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.kes.tolerations.withValue

```ts
withValue(value)
```



## obj spec.kes.topologySpreadConstraints



### fn spec.kes.topologySpreadConstraints.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.kes.topologySpreadConstraints.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.topologySpreadConstraints.withMaxSkew

```ts
withMaxSkew(maxSkew)
```



### fn spec.kes.topologySpreadConstraints.withMinDomains

```ts
withMinDomains(minDomains)
```



### fn spec.kes.topologySpreadConstraints.withNodeAffinityPolicy

```ts
withNodeAffinityPolicy(nodeAffinityPolicy)
```



### fn spec.kes.topologySpreadConstraints.withNodeTaintsPolicy

```ts
withNodeTaintsPolicy(nodeTaintsPolicy)
```



### fn spec.kes.topologySpreadConstraints.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



### fn spec.kes.topologySpreadConstraints.withWhenUnsatisfiable

```ts
withWhenUnsatisfiable(whenUnsatisfiable)
```



## obj spec.kes.topologySpreadConstraints.labelSelector



### fn spec.kes.topologySpreadConstraints.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.kes.topologySpreadConstraints.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.kes.topologySpreadConstraints.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.kes.topologySpreadConstraints.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.kes.topologySpreadConstraints.labelSelector.matchExpressions



### fn spec.kes.topologySpreadConstraints.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.kes.topologySpreadConstraints.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.kes.topologySpreadConstraints.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.kes.topologySpreadConstraints.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.lifecycle



## obj spec.lifecycle.postStart



## obj spec.lifecycle.postStart.exec



### fn spec.lifecycle.postStart.exec.withCommand

```ts
withCommand(command)
```



### fn spec.lifecycle.postStart.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.lifecycle.postStart.httpGet



### fn spec.lifecycle.postStart.httpGet.withHost

```ts
withHost(host)
```



### fn spec.lifecycle.postStart.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.lifecycle.postStart.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.lifecycle.postStart.httpGet.withPath

```ts
withPath(path)
```



### fn spec.lifecycle.postStart.httpGet.withPort

```ts
withPort(port)
```



### fn spec.lifecycle.postStart.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.lifecycle.postStart.httpGet.httpHeaders



### fn spec.lifecycle.postStart.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.lifecycle.postStart.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.lifecycle.postStart.tcpSocket



### fn spec.lifecycle.postStart.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.lifecycle.postStart.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.lifecycle.preStop



## obj spec.lifecycle.preStop.exec



### fn spec.lifecycle.preStop.exec.withCommand

```ts
withCommand(command)
```



### fn spec.lifecycle.preStop.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.lifecycle.preStop.httpGet



### fn spec.lifecycle.preStop.httpGet.withHost

```ts
withHost(host)
```



### fn spec.lifecycle.preStop.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.lifecycle.preStop.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.lifecycle.preStop.httpGet.withPath

```ts
withPath(path)
```



### fn spec.lifecycle.preStop.httpGet.withPort

```ts
withPort(port)
```



### fn spec.lifecycle.preStop.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.lifecycle.preStop.httpGet.httpHeaders



### fn spec.lifecycle.preStop.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.lifecycle.preStop.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.lifecycle.preStop.tcpSocket



### fn spec.lifecycle.preStop.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.lifecycle.preStop.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.liveness



### fn spec.liveness.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.liveness.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.liveness.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.liveness.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.liveness.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.liveness.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.liveness.exec



### fn spec.liveness.exec.withCommand

```ts
withCommand(command)
```



### fn spec.liveness.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.liveness.grpc



### fn spec.liveness.grpc.withPort

```ts
withPort(port)
```



### fn spec.liveness.grpc.withService

```ts
withService(service)
```



## obj spec.liveness.httpGet



### fn spec.liveness.httpGet.withHost

```ts
withHost(host)
```



### fn spec.liveness.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.liveness.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.liveness.httpGet.withPath

```ts
withPath(path)
```



### fn spec.liveness.httpGet.withPort

```ts
withPort(port)
```



### fn spec.liveness.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.liveness.httpGet.httpHeaders



### fn spec.liveness.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.liveness.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.liveness.tcpSocket



### fn spec.liveness.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.liveness.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.logging



### fn spec.logging.withAnonymous

```ts
withAnonymous(anonymous)
```



### fn spec.logging.withJson

```ts
withJson(json)
```



### fn spec.logging.withQuiet

```ts
withQuiet(quiet)
```



## obj spec.pools



### fn spec.pools.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.pools.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.withLabels

```ts
withLabels(labels)
```



### fn spec.pools.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.withName

```ts
withName(name)
```



### fn spec.pools.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.pools.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.withReclaimStorage

```ts
withReclaimStorage(reclaimStorage)
```



### fn spec.pools.withRuntimeClassName

```ts
withRuntimeClassName(runtimeClassName)
```



### fn spec.pools.withServers

```ts
withServers(servers)
```



### fn spec.pools.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.pools.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.withTopologySpreadConstraints

```ts
withTopologySpreadConstraints(topologySpreadConstraints)
```



### fn spec.pools.withTopologySpreadConstraintsMixin

```ts
withTopologySpreadConstraintsMixin(topologySpreadConstraints)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.withVolumesPerServer

```ts
withVolumesPerServer(volumesPerServer)
```



## obj spec.pools.affinity



## obj spec.pools.affinity.nodeAffinity



### fn spec.pools.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.pools.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.pools.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.pools.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.podAffinity



### fn spec.pools.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.pools.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.pools.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.pools.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.pools.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.podAntiAffinity



### fn spec.pools.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.pools.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.pools.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.pools.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.pools.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.containerSecurityContext



### fn spec.pools.containerSecurityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```



### fn spec.pools.containerSecurityContext.withPrivileged

```ts
withPrivileged(privileged)
```



### fn spec.pools.containerSecurityContext.withProcMount

```ts
withProcMount(procMount)
```



### fn spec.pools.containerSecurityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```



### fn spec.pools.containerSecurityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.pools.containerSecurityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.pools.containerSecurityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



## obj spec.pools.containerSecurityContext.capabilities



### fn spec.pools.containerSecurityContext.capabilities.withAdd

```ts
withAdd(add)
```



### fn spec.pools.containerSecurityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.containerSecurityContext.capabilities.withDrop

```ts
withDrop(drop)
```



### fn spec.pools.containerSecurityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.containerSecurityContext.seLinuxOptions



### fn spec.pools.containerSecurityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.pools.containerSecurityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.pools.containerSecurityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.pools.containerSecurityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.pools.containerSecurityContext.seccompProfile



### fn spec.pools.containerSecurityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.pools.containerSecurityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.pools.containerSecurityContext.windowsOptions



### fn spec.pools.containerSecurityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.pools.containerSecurityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.pools.containerSecurityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.pools.containerSecurityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.pools.resources



### fn spec.pools.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.pools.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.pools.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.pools.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.resources.claims



### fn spec.pools.resources.claims.withName

```ts
withName(name)
```



## obj spec.pools.securityContext



### fn spec.pools.securityContext.withFsGroup

```ts
withFsGroup(fsGroup)
```



### fn spec.pools.securityContext.withFsGroupChangePolicy

```ts
withFsGroupChangePolicy(fsGroupChangePolicy)
```



### fn spec.pools.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.pools.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.pools.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



### fn spec.pools.securityContext.withSupplementalGroups

```ts
withSupplementalGroups(supplementalGroups)
```



### fn spec.pools.securityContext.withSupplementalGroupsMixin

```ts
withSupplementalGroupsMixin(supplementalGroups)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.securityContext.withSysctls

```ts
withSysctls(sysctls)
```



### fn spec.pools.securityContext.withSysctlsMixin

```ts
withSysctlsMixin(sysctls)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.securityContext.seLinuxOptions



### fn spec.pools.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.pools.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.pools.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.pools.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.pools.securityContext.seccompProfile



### fn spec.pools.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.pools.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.pools.securityContext.sysctls



### fn spec.pools.securityContext.sysctls.withName

```ts
withName(name)
```



### fn spec.pools.securityContext.sysctls.withValue

```ts
withValue(value)
```



## obj spec.pools.securityContext.windowsOptions



### fn spec.pools.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.pools.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.pools.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.pools.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.pools.tolerations



### fn spec.pools.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.pools.tolerations.withKey

```ts
withKey(key)
```



### fn spec.pools.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.pools.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.pools.tolerations.withValue

```ts
withValue(value)
```



## obj spec.pools.topologySpreadConstraints



### fn spec.pools.topologySpreadConstraints.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.pools.topologySpreadConstraints.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.topologySpreadConstraints.withMaxSkew

```ts
withMaxSkew(maxSkew)
```



### fn spec.pools.topologySpreadConstraints.withMinDomains

```ts
withMinDomains(minDomains)
```



### fn spec.pools.topologySpreadConstraints.withNodeAffinityPolicy

```ts
withNodeAffinityPolicy(nodeAffinityPolicy)
```



### fn spec.pools.topologySpreadConstraints.withNodeTaintsPolicy

```ts
withNodeTaintsPolicy(nodeTaintsPolicy)
```



### fn spec.pools.topologySpreadConstraints.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



### fn spec.pools.topologySpreadConstraints.withWhenUnsatisfiable

```ts
withWhenUnsatisfiable(whenUnsatisfiable)
```



## obj spec.pools.topologySpreadConstraints.labelSelector



### fn spec.pools.topologySpreadConstraints.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.pools.topologySpreadConstraints.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.topologySpreadConstraints.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.pools.topologySpreadConstraints.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.topologySpreadConstraints.labelSelector.matchExpressions



### fn spec.pools.topologySpreadConstraints.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.pools.topologySpreadConstraints.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.pools.topologySpreadConstraints.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.pools.topologySpreadConstraints.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.volumeClaimTemplate



### fn spec.pools.volumeClaimTemplate.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.pools.volumeClaimTemplate.withKind

```ts
withKind(kind)
```



## obj spec.pools.volumeClaimTemplate.metadata



### fn spec.pools.volumeClaimTemplate.metadata.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.pools.volumeClaimTemplate.metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.volumeClaimTemplate.metadata.withFinalizers

```ts
withFinalizers(finalizers)
```



### fn spec.pools.volumeClaimTemplate.metadata.withFinalizersMixin

```ts
withFinalizersMixin(finalizers)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.volumeClaimTemplate.metadata.withLabels

```ts
withLabels(labels)
```



### fn spec.pools.volumeClaimTemplate.metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.volumeClaimTemplate.metadata.withName

```ts
withName(name)
```



### fn spec.pools.volumeClaimTemplate.metadata.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.pools.volumeClaimTemplate.spec



### fn spec.pools.volumeClaimTemplate.spec.withAccessModes

```ts
withAccessModes(accessModes)
```



### fn spec.pools.volumeClaimTemplate.spec.withAccessModesMixin

```ts
withAccessModesMixin(accessModes)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.volumeClaimTemplate.spec.withStorageClassName

```ts
withStorageClassName(storageClassName)
```



### fn spec.pools.volumeClaimTemplate.spec.withVolumeAttributesClassName

```ts
withVolumeAttributesClassName(volumeAttributesClassName)
```



### fn spec.pools.volumeClaimTemplate.spec.withVolumeMode

```ts
withVolumeMode(volumeMode)
```



### fn spec.pools.volumeClaimTemplate.spec.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.pools.volumeClaimTemplate.spec.dataSource



### fn spec.pools.volumeClaimTemplate.spec.dataSource.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.pools.volumeClaimTemplate.spec.dataSource.withKind

```ts
withKind(kind)
```



### fn spec.pools.volumeClaimTemplate.spec.dataSource.withName

```ts
withName(name)
```



## obj spec.pools.volumeClaimTemplate.spec.dataSourceRef



### fn spec.pools.volumeClaimTemplate.spec.dataSourceRef.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.pools.volumeClaimTemplate.spec.dataSourceRef.withKind

```ts
withKind(kind)
```



### fn spec.pools.volumeClaimTemplate.spec.dataSourceRef.withName

```ts
withName(name)
```



### fn spec.pools.volumeClaimTemplate.spec.dataSourceRef.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.pools.volumeClaimTemplate.spec.resources



### fn spec.pools.volumeClaimTemplate.spec.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.pools.volumeClaimTemplate.spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.volumeClaimTemplate.spec.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.pools.volumeClaimTemplate.spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.volumeClaimTemplate.spec.selector



### fn spec.pools.volumeClaimTemplate.spec.selector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.pools.volumeClaimTemplate.spec.selector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.pools.volumeClaimTemplate.spec.selector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.pools.volumeClaimTemplate.spec.selector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.pools.volumeClaimTemplate.spec.selector.matchExpressions



### fn spec.pools.volumeClaimTemplate.spec.selector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.pools.volumeClaimTemplate.spec.selector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.pools.volumeClaimTemplate.spec.selector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.pools.volumeClaimTemplate.spec.selector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.readiness



### fn spec.readiness.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.readiness.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.readiness.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.readiness.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.readiness.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.readiness.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.readiness.exec



### fn spec.readiness.exec.withCommand

```ts
withCommand(command)
```



### fn spec.readiness.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.readiness.grpc



### fn spec.readiness.grpc.withPort

```ts
withPort(port)
```



### fn spec.readiness.grpc.withService

```ts
withService(service)
```



## obj spec.readiness.httpGet



### fn spec.readiness.httpGet.withHost

```ts
withHost(host)
```



### fn spec.readiness.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.readiness.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.readiness.httpGet.withPath

```ts
withPath(path)
```



### fn spec.readiness.httpGet.withPort

```ts
withPort(port)
```



### fn spec.readiness.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.readiness.httpGet.httpHeaders



### fn spec.readiness.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.readiness.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.readiness.tcpSocket



### fn spec.readiness.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.readiness.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.serviceMetadata



### fn spec.serviceMetadata.withConsoleServiceAnnotations

```ts
withConsoleServiceAnnotations(consoleServiceAnnotations)
```



### fn spec.serviceMetadata.withConsoleServiceAnnotationsMixin

```ts
withConsoleServiceAnnotationsMixin(consoleServiceAnnotations)
```



**Note:** This function appends passed data to existing values

### fn spec.serviceMetadata.withConsoleServiceLabels

```ts
withConsoleServiceLabels(consoleServiceLabels)
```



### fn spec.serviceMetadata.withConsoleServiceLabelsMixin

```ts
withConsoleServiceLabelsMixin(consoleServiceLabels)
```



**Note:** This function appends passed data to existing values

### fn spec.serviceMetadata.withMinioServiceAnnotations

```ts
withMinioServiceAnnotations(minioServiceAnnotations)
```



### fn spec.serviceMetadata.withMinioServiceAnnotationsMixin

```ts
withMinioServiceAnnotationsMixin(minioServiceAnnotations)
```



**Note:** This function appends passed data to existing values

### fn spec.serviceMetadata.withMinioServiceLabels

```ts
withMinioServiceLabels(minioServiceLabels)
```



### fn spec.serviceMetadata.withMinioServiceLabelsMixin

```ts
withMinioServiceLabelsMixin(minioServiceLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars



### fn spec.sideCars.withContainers

```ts
withContainers(containers)
```



### fn spec.sideCars.withContainersMixin

```ts
withContainersMixin(containers)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.withVolumeClaimTemplates

```ts
withVolumeClaimTemplates(volumeClaimTemplates)
```



### fn spec.sideCars.withVolumeClaimTemplatesMixin

```ts
withVolumeClaimTemplatesMixin(volumeClaimTemplates)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.withVolumes

```ts
withVolumes(volumes)
```



### fn spec.sideCars.withVolumesMixin

```ts
withVolumesMixin(volumes)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.containers



### fn spec.sideCars.containers.withArgs

```ts
withArgs(args)
```



### fn spec.sideCars.containers.withArgsMixin

```ts
withArgsMixin(args)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.containers.withCommand

```ts
withCommand(command)
```



### fn spec.sideCars.containers.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.containers.withEnv

```ts
withEnv(env)
```



### fn spec.sideCars.containers.withEnvFrom

```ts
withEnvFrom(envFrom)
```



### fn spec.sideCars.containers.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.containers.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.containers.withImage

```ts
withImage(image)
```



### fn spec.sideCars.containers.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.sideCars.containers.withName

```ts
withName(name)
```



### fn spec.sideCars.containers.withPorts

```ts
withPorts(ports)
```



### fn spec.sideCars.containers.withPortsMixin

```ts
withPortsMixin(ports)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.containers.withResizePolicy

```ts
withResizePolicy(resizePolicy)
```



### fn spec.sideCars.containers.withResizePolicyMixin

```ts
withResizePolicyMixin(resizePolicy)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.containers.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



### fn spec.sideCars.containers.withStdin

```ts
withStdin(stdin)
```



### fn spec.sideCars.containers.withStdinOnce

```ts
withStdinOnce(stdinOnce)
```



### fn spec.sideCars.containers.withTerminationMessagePath

```ts
withTerminationMessagePath(terminationMessagePath)
```



### fn spec.sideCars.containers.withTerminationMessagePolicy

```ts
withTerminationMessagePolicy(terminationMessagePolicy)
```



### fn spec.sideCars.containers.withTty

```ts
withTty(tty)
```



### fn spec.sideCars.containers.withVolumeDevices

```ts
withVolumeDevices(volumeDevices)
```



### fn spec.sideCars.containers.withVolumeDevicesMixin

```ts
withVolumeDevicesMixin(volumeDevices)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.containers.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.sideCars.containers.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.containers.withWorkingDir

```ts
withWorkingDir(workingDir)
```



## obj spec.sideCars.containers.env



### fn spec.sideCars.containers.env.withName

```ts
withName(name)
```



### fn spec.sideCars.containers.env.withValue

```ts
withValue(value)
```



## obj spec.sideCars.containers.env.valueFrom



## obj spec.sideCars.containers.env.valueFrom.configMapKeyRef



### fn spec.sideCars.containers.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.sideCars.containers.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.sideCars.containers.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.sideCars.containers.env.valueFrom.fieldRef



### fn spec.sideCars.containers.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.sideCars.containers.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.sideCars.containers.env.valueFrom.resourceFieldRef



### fn spec.sideCars.containers.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.sideCars.containers.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.sideCars.containers.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.sideCars.containers.env.valueFrom.secretKeyRef



### fn spec.sideCars.containers.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.sideCars.containers.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.sideCars.containers.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.sideCars.containers.envFrom



### fn spec.sideCars.containers.envFrom.withPrefix

```ts
withPrefix(prefix)
```



## obj spec.sideCars.containers.envFrom.configMapRef



### fn spec.sideCars.containers.envFrom.configMapRef.withName

```ts
withName(name)
```



### fn spec.sideCars.containers.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```



## obj spec.sideCars.containers.envFrom.secretRef



### fn spec.sideCars.containers.envFrom.secretRef.withName

```ts
withName(name)
```



### fn spec.sideCars.containers.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```



## obj spec.sideCars.containers.lifecycle



## obj spec.sideCars.containers.lifecycle.postStart



## obj spec.sideCars.containers.lifecycle.postStart.exec



### fn spec.sideCars.containers.lifecycle.postStart.exec.withCommand

```ts
withCommand(command)
```



### fn spec.sideCars.containers.lifecycle.postStart.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.containers.lifecycle.postStart.httpGet



### fn spec.sideCars.containers.lifecycle.postStart.httpGet.withHost

```ts
withHost(host)
```



### fn spec.sideCars.containers.lifecycle.postStart.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.sideCars.containers.lifecycle.postStart.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.containers.lifecycle.postStart.httpGet.withPath

```ts
withPath(path)
```



### fn spec.sideCars.containers.lifecycle.postStart.httpGet.withPort

```ts
withPort(port)
```



### fn spec.sideCars.containers.lifecycle.postStart.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.sideCars.containers.lifecycle.postStart.httpGet.httpHeaders



### fn spec.sideCars.containers.lifecycle.postStart.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.sideCars.containers.lifecycle.postStart.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.sideCars.containers.lifecycle.postStart.sleep



### fn spec.sideCars.containers.lifecycle.postStart.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.sideCars.containers.lifecycle.postStart.tcpSocket



### fn spec.sideCars.containers.lifecycle.postStart.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.sideCars.containers.lifecycle.postStart.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.sideCars.containers.lifecycle.preStop



## obj spec.sideCars.containers.lifecycle.preStop.exec



### fn spec.sideCars.containers.lifecycle.preStop.exec.withCommand

```ts
withCommand(command)
```



### fn spec.sideCars.containers.lifecycle.preStop.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.containers.lifecycle.preStop.httpGet



### fn spec.sideCars.containers.lifecycle.preStop.httpGet.withHost

```ts
withHost(host)
```



### fn spec.sideCars.containers.lifecycle.preStop.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.sideCars.containers.lifecycle.preStop.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.containers.lifecycle.preStop.httpGet.withPath

```ts
withPath(path)
```



### fn spec.sideCars.containers.lifecycle.preStop.httpGet.withPort

```ts
withPort(port)
```



### fn spec.sideCars.containers.lifecycle.preStop.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.sideCars.containers.lifecycle.preStop.httpGet.httpHeaders



### fn spec.sideCars.containers.lifecycle.preStop.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.sideCars.containers.lifecycle.preStop.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.sideCars.containers.lifecycle.preStop.sleep



### fn spec.sideCars.containers.lifecycle.preStop.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.sideCars.containers.lifecycle.preStop.tcpSocket



### fn spec.sideCars.containers.lifecycle.preStop.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.sideCars.containers.lifecycle.preStop.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.sideCars.containers.livenessProbe



### fn spec.sideCars.containers.livenessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.sideCars.containers.livenessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.sideCars.containers.livenessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.sideCars.containers.livenessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.sideCars.containers.livenessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.sideCars.containers.livenessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.sideCars.containers.livenessProbe.exec



### fn spec.sideCars.containers.livenessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.sideCars.containers.livenessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.containers.livenessProbe.grpc



### fn spec.sideCars.containers.livenessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.sideCars.containers.livenessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.sideCars.containers.livenessProbe.httpGet



### fn spec.sideCars.containers.livenessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.sideCars.containers.livenessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.sideCars.containers.livenessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.containers.livenessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.sideCars.containers.livenessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.sideCars.containers.livenessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.sideCars.containers.livenessProbe.httpGet.httpHeaders



### fn spec.sideCars.containers.livenessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.sideCars.containers.livenessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.sideCars.containers.livenessProbe.tcpSocket



### fn spec.sideCars.containers.livenessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.sideCars.containers.livenessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.sideCars.containers.ports



### fn spec.sideCars.containers.ports.withContainerPort

```ts
withContainerPort(containerPort)
```



### fn spec.sideCars.containers.ports.withHostIP

```ts
withHostIP(hostIP)
```



### fn spec.sideCars.containers.ports.withHostPort

```ts
withHostPort(hostPort)
```



### fn spec.sideCars.containers.ports.withName

```ts
withName(name)
```



### fn spec.sideCars.containers.ports.withProtocol

```ts
withProtocol(protocol)
```



## obj spec.sideCars.containers.readinessProbe



### fn spec.sideCars.containers.readinessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.sideCars.containers.readinessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.sideCars.containers.readinessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.sideCars.containers.readinessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.sideCars.containers.readinessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.sideCars.containers.readinessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.sideCars.containers.readinessProbe.exec



### fn spec.sideCars.containers.readinessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.sideCars.containers.readinessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.containers.readinessProbe.grpc



### fn spec.sideCars.containers.readinessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.sideCars.containers.readinessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.sideCars.containers.readinessProbe.httpGet



### fn spec.sideCars.containers.readinessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.sideCars.containers.readinessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.sideCars.containers.readinessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.containers.readinessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.sideCars.containers.readinessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.sideCars.containers.readinessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.sideCars.containers.readinessProbe.httpGet.httpHeaders



### fn spec.sideCars.containers.readinessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.sideCars.containers.readinessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.sideCars.containers.readinessProbe.tcpSocket



### fn spec.sideCars.containers.readinessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.sideCars.containers.readinessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.sideCars.containers.resizePolicy



### fn spec.sideCars.containers.resizePolicy.withResourceName

```ts
withResourceName(resourceName)
```



### fn spec.sideCars.containers.resizePolicy.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



## obj spec.sideCars.containers.resources



### fn spec.sideCars.containers.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.sideCars.containers.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.containers.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.sideCars.containers.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.containers.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.sideCars.containers.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.containers.resources.claims



### fn spec.sideCars.containers.resources.claims.withName

```ts
withName(name)
```



## obj spec.sideCars.containers.securityContext



### fn spec.sideCars.containers.securityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```



### fn spec.sideCars.containers.securityContext.withPrivileged

```ts
withPrivileged(privileged)
```



### fn spec.sideCars.containers.securityContext.withProcMount

```ts
withProcMount(procMount)
```



### fn spec.sideCars.containers.securityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```



### fn spec.sideCars.containers.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.sideCars.containers.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.sideCars.containers.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



## obj spec.sideCars.containers.securityContext.capabilities



### fn spec.sideCars.containers.securityContext.capabilities.withAdd

```ts
withAdd(add)
```



### fn spec.sideCars.containers.securityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.containers.securityContext.capabilities.withDrop

```ts
withDrop(drop)
```



### fn spec.sideCars.containers.securityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.containers.securityContext.seLinuxOptions



### fn spec.sideCars.containers.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.sideCars.containers.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.sideCars.containers.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.sideCars.containers.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.sideCars.containers.securityContext.seccompProfile



### fn spec.sideCars.containers.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.sideCars.containers.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.sideCars.containers.securityContext.windowsOptions



### fn spec.sideCars.containers.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.sideCars.containers.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.sideCars.containers.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.sideCars.containers.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.sideCars.containers.startupProbe



### fn spec.sideCars.containers.startupProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.sideCars.containers.startupProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.sideCars.containers.startupProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.sideCars.containers.startupProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.sideCars.containers.startupProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.sideCars.containers.startupProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.sideCars.containers.startupProbe.exec



### fn spec.sideCars.containers.startupProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.sideCars.containers.startupProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.containers.startupProbe.grpc



### fn spec.sideCars.containers.startupProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.sideCars.containers.startupProbe.grpc.withService

```ts
withService(service)
```



## obj spec.sideCars.containers.startupProbe.httpGet



### fn spec.sideCars.containers.startupProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.sideCars.containers.startupProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.sideCars.containers.startupProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.containers.startupProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.sideCars.containers.startupProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.sideCars.containers.startupProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.sideCars.containers.startupProbe.httpGet.httpHeaders



### fn spec.sideCars.containers.startupProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.sideCars.containers.startupProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.sideCars.containers.startupProbe.tcpSocket



### fn spec.sideCars.containers.startupProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.sideCars.containers.startupProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.sideCars.containers.volumeDevices



### fn spec.sideCars.containers.volumeDevices.withDevicePath

```ts
withDevicePath(devicePath)
```



### fn spec.sideCars.containers.volumeDevices.withName

```ts
withName(name)
```



## obj spec.sideCars.containers.volumeMounts



### fn spec.sideCars.containers.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.sideCars.containers.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.sideCars.containers.volumeMounts.withName

```ts
withName(name)
```



### fn spec.sideCars.containers.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.sideCars.containers.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.sideCars.containers.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.sideCars.resources



### fn spec.sideCars.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.sideCars.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.sideCars.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.sideCars.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.resources.claims



### fn spec.sideCars.resources.claims.withName

```ts
withName(name)
```



## obj spec.sideCars.volumeClaimTemplates



### fn spec.sideCars.volumeClaimTemplates.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.sideCars.volumeClaimTemplates.withKind

```ts
withKind(kind)
```



## obj spec.sideCars.volumeClaimTemplates.metadata



### fn spec.sideCars.volumeClaimTemplates.metadata.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.sideCars.volumeClaimTemplates.metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumeClaimTemplates.metadata.withFinalizers

```ts
withFinalizers(finalizers)
```



### fn spec.sideCars.volumeClaimTemplates.metadata.withFinalizersMixin

```ts
withFinalizersMixin(finalizers)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumeClaimTemplates.metadata.withLabels

```ts
withLabels(labels)
```



### fn spec.sideCars.volumeClaimTemplates.metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumeClaimTemplates.metadata.withName

```ts
withName(name)
```



### fn spec.sideCars.volumeClaimTemplates.metadata.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.sideCars.volumeClaimTemplates.spec



### fn spec.sideCars.volumeClaimTemplates.spec.withAccessModes

```ts
withAccessModes(accessModes)
```



### fn spec.sideCars.volumeClaimTemplates.spec.withAccessModesMixin

```ts
withAccessModesMixin(accessModes)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumeClaimTemplates.spec.withStorageClassName

```ts
withStorageClassName(storageClassName)
```



### fn spec.sideCars.volumeClaimTemplates.spec.withVolumeAttributesClassName

```ts
withVolumeAttributesClassName(volumeAttributesClassName)
```



### fn spec.sideCars.volumeClaimTemplates.spec.withVolumeMode

```ts
withVolumeMode(volumeMode)
```



### fn spec.sideCars.volumeClaimTemplates.spec.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.sideCars.volumeClaimTemplates.spec.dataSource



### fn spec.sideCars.volumeClaimTemplates.spec.dataSource.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.sideCars.volumeClaimTemplates.spec.dataSource.withKind

```ts
withKind(kind)
```



### fn spec.sideCars.volumeClaimTemplates.spec.dataSource.withName

```ts
withName(name)
```



## obj spec.sideCars.volumeClaimTemplates.spec.dataSourceRef



### fn spec.sideCars.volumeClaimTemplates.spec.dataSourceRef.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.sideCars.volumeClaimTemplates.spec.dataSourceRef.withKind

```ts
withKind(kind)
```



### fn spec.sideCars.volumeClaimTemplates.spec.dataSourceRef.withName

```ts
withName(name)
```



### fn spec.sideCars.volumeClaimTemplates.spec.dataSourceRef.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.sideCars.volumeClaimTemplates.spec.resources



### fn spec.sideCars.volumeClaimTemplates.spec.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.sideCars.volumeClaimTemplates.spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumeClaimTemplates.spec.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.sideCars.volumeClaimTemplates.spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.volumeClaimTemplates.spec.selector



### fn spec.sideCars.volumeClaimTemplates.spec.selector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.sideCars.volumeClaimTemplates.spec.selector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumeClaimTemplates.spec.selector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.sideCars.volumeClaimTemplates.spec.selector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.volumeClaimTemplates.spec.selector.matchExpressions



### fn spec.sideCars.volumeClaimTemplates.spec.selector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.sideCars.volumeClaimTemplates.spec.selector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.sideCars.volumeClaimTemplates.spec.selector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.sideCars.volumeClaimTemplates.spec.selector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.volumes



### fn spec.sideCars.volumes.withName

```ts
withName(name)
```



## obj spec.sideCars.volumes.awsElasticBlockStore



### fn spec.sideCars.volumes.awsElasticBlockStore.withFsType

```ts
withFsType(fsType)
```



### fn spec.sideCars.volumes.awsElasticBlockStore.withPartition

```ts
withPartition(partition)
```



### fn spec.sideCars.volumes.awsElasticBlockStore.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.sideCars.volumes.awsElasticBlockStore.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.sideCars.volumes.azureDisk



### fn spec.sideCars.volumes.azureDisk.withCachingMode

```ts
withCachingMode(cachingMode)
```



### fn spec.sideCars.volumes.azureDisk.withDiskName

```ts
withDiskName(diskName)
```



### fn spec.sideCars.volumes.azureDisk.withDiskURI

```ts
withDiskURI(diskURI)
```



### fn spec.sideCars.volumes.azureDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.sideCars.volumes.azureDisk.withKind

```ts
withKind(kind)
```



### fn spec.sideCars.volumes.azureDisk.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.sideCars.volumes.azureFile



### fn spec.sideCars.volumes.azureFile.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.sideCars.volumes.azureFile.withSecretName

```ts
withSecretName(secretName)
```



### fn spec.sideCars.volumes.azureFile.withShareName

```ts
withShareName(shareName)
```



## obj spec.sideCars.volumes.cephfs



### fn spec.sideCars.volumes.cephfs.withMonitors

```ts
withMonitors(monitors)
```



### fn spec.sideCars.volumes.cephfs.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumes.cephfs.withPath

```ts
withPath(path)
```



### fn spec.sideCars.volumes.cephfs.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.sideCars.volumes.cephfs.withSecretFile

```ts
withSecretFile(secretFile)
```



### fn spec.sideCars.volumes.cephfs.withUser

```ts
withUser(user)
```



## obj spec.sideCars.volumes.cephfs.secretRef



### fn spec.sideCars.volumes.cephfs.secretRef.withName

```ts
withName(name)
```



## obj spec.sideCars.volumes.cinder



### fn spec.sideCars.volumes.cinder.withFsType

```ts
withFsType(fsType)
```



### fn spec.sideCars.volumes.cinder.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.sideCars.volumes.cinder.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.sideCars.volumes.cinder.secretRef



### fn spec.sideCars.volumes.cinder.secretRef.withName

```ts
withName(name)
```



## obj spec.sideCars.volumes.configMap



### fn spec.sideCars.volumes.configMap.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.sideCars.volumes.configMap.withItems

```ts
withItems(items)
```



### fn spec.sideCars.volumes.configMap.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumes.configMap.withName

```ts
withName(name)
```



### fn spec.sideCars.volumes.configMap.withOptional

```ts
withOptional(optional)
```



## obj spec.sideCars.volumes.configMap.items



### fn spec.sideCars.volumes.configMap.items.withKey

```ts
withKey(key)
```



### fn spec.sideCars.volumes.configMap.items.withMode

```ts
withMode(mode)
```



### fn spec.sideCars.volumes.configMap.items.withPath

```ts
withPath(path)
```



## obj spec.sideCars.volumes.csi



### fn spec.sideCars.volumes.csi.withDriver

```ts
withDriver(driver)
```



### fn spec.sideCars.volumes.csi.withFsType

```ts
withFsType(fsType)
```



### fn spec.sideCars.volumes.csi.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.sideCars.volumes.csi.withVolumeAttributes

```ts
withVolumeAttributes(volumeAttributes)
```



### fn spec.sideCars.volumes.csi.withVolumeAttributesMixin

```ts
withVolumeAttributesMixin(volumeAttributes)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.volumes.csi.nodePublishSecretRef



### fn spec.sideCars.volumes.csi.nodePublishSecretRef.withName

```ts
withName(name)
```



## obj spec.sideCars.volumes.downwardAPI



### fn spec.sideCars.volumes.downwardAPI.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.sideCars.volumes.downwardAPI.withItems

```ts
withItems(items)
```



### fn spec.sideCars.volumes.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.volumes.downwardAPI.items



### fn spec.sideCars.volumes.downwardAPI.items.withMode

```ts
withMode(mode)
```



### fn spec.sideCars.volumes.downwardAPI.items.withPath

```ts
withPath(path)
```



## obj spec.sideCars.volumes.downwardAPI.items.fieldRef



### fn spec.sideCars.volumes.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.sideCars.volumes.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.sideCars.volumes.downwardAPI.items.resourceFieldRef



### fn spec.sideCars.volumes.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.sideCars.volumes.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.sideCars.volumes.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.sideCars.volumes.emptyDir



### fn spec.sideCars.volumes.emptyDir.withMedium

```ts
withMedium(medium)
```



### fn spec.sideCars.volumes.emptyDir.withSizeLimit

```ts
withSizeLimit(sizeLimit)
```



## obj spec.sideCars.volumes.ephemeral



## obj spec.sideCars.volumes.ephemeral.volumeClaimTemplate



## obj spec.sideCars.volumes.ephemeral.volumeClaimTemplate.metadata



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.metadata.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.metadata.withFinalizers

```ts
withFinalizers(finalizers)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.metadata.withFinalizersMixin

```ts
withFinalizersMixin(finalizers)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.metadata.withLabels

```ts
withLabels(labels)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.metadata.withName

```ts
withName(name)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.metadata.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.withAccessModes

```ts
withAccessModes(accessModes)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.withAccessModesMixin

```ts
withAccessModesMixin(accessModes)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.withStorageClassName

```ts
withStorageClassName(storageClassName)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeAttributesClassName

```ts
withVolumeAttributesClassName(volumeAttributesClassName)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeMode

```ts
withVolumeMode(volumeMode)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.dataSource



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withKind

```ts
withKind(kind)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withName

```ts
withName(name)
```



## obj spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withKind

```ts
withKind(kind)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withName

```ts
withName(name)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.resources



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.selector



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.sideCars.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.volumes.fc



### fn spec.sideCars.volumes.fc.withFsType

```ts
withFsType(fsType)
```



### fn spec.sideCars.volumes.fc.withLun

```ts
withLun(lun)
```



### fn spec.sideCars.volumes.fc.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.sideCars.volumes.fc.withTargetWWNs

```ts
withTargetWWNs(targetWWNs)
```



### fn spec.sideCars.volumes.fc.withTargetWWNsMixin

```ts
withTargetWWNsMixin(targetWWNs)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumes.fc.withWwids

```ts
withWwids(wwids)
```



### fn spec.sideCars.volumes.fc.withWwidsMixin

```ts
withWwidsMixin(wwids)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.volumes.flexVolume



### fn spec.sideCars.volumes.flexVolume.withDriver

```ts
withDriver(driver)
```



### fn spec.sideCars.volumes.flexVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.sideCars.volumes.flexVolume.withOptions

```ts
withOptions(options)
```



### fn spec.sideCars.volumes.flexVolume.withOptionsMixin

```ts
withOptionsMixin(options)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumes.flexVolume.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.sideCars.volumes.flexVolume.secretRef



### fn spec.sideCars.volumes.flexVolume.secretRef.withName

```ts
withName(name)
```



## obj spec.sideCars.volumes.flocker



### fn spec.sideCars.volumes.flocker.withDatasetName

```ts
withDatasetName(datasetName)
```



### fn spec.sideCars.volumes.flocker.withDatasetUUID

```ts
withDatasetUUID(datasetUUID)
```



## obj spec.sideCars.volumes.gcePersistentDisk



### fn spec.sideCars.volumes.gcePersistentDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.sideCars.volumes.gcePersistentDisk.withPartition

```ts
withPartition(partition)
```



### fn spec.sideCars.volumes.gcePersistentDisk.withPdName

```ts
withPdName(pdName)
```



### fn spec.sideCars.volumes.gcePersistentDisk.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.sideCars.volumes.gitRepo



### fn spec.sideCars.volumes.gitRepo.withDirectory

```ts
withDirectory(directory)
```



### fn spec.sideCars.volumes.gitRepo.withRepository

```ts
withRepository(repository)
```



### fn spec.sideCars.volumes.gitRepo.withRevision

```ts
withRevision(revision)
```



## obj spec.sideCars.volumes.glusterfs



### fn spec.sideCars.volumes.glusterfs.withEndpoints

```ts
withEndpoints(endpoints)
```



### fn spec.sideCars.volumes.glusterfs.withPath

```ts
withPath(path)
```



### fn spec.sideCars.volumes.glusterfs.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.sideCars.volumes.hostPath



### fn spec.sideCars.volumes.hostPath.withPath

```ts
withPath(path)
```



### fn spec.sideCars.volumes.hostPath.withType

```ts
withType(type)
```



## obj spec.sideCars.volumes.iscsi



### fn spec.sideCars.volumes.iscsi.withChapAuthDiscovery

```ts
withChapAuthDiscovery(chapAuthDiscovery)
```



### fn spec.sideCars.volumes.iscsi.withChapAuthSession

```ts
withChapAuthSession(chapAuthSession)
```



### fn spec.sideCars.volumes.iscsi.withFsType

```ts
withFsType(fsType)
```



### fn spec.sideCars.volumes.iscsi.withInitiatorName

```ts
withInitiatorName(initiatorName)
```



### fn spec.sideCars.volumes.iscsi.withIqn

```ts
withIqn(iqn)
```



### fn spec.sideCars.volumes.iscsi.withIscsiInterface

```ts
withIscsiInterface(iscsiInterface)
```



### fn spec.sideCars.volumes.iscsi.withLun

```ts
withLun(lun)
```



### fn spec.sideCars.volumes.iscsi.withPortals

```ts
withPortals(portals)
```



### fn spec.sideCars.volumes.iscsi.withPortalsMixin

```ts
withPortalsMixin(portals)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumes.iscsi.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.sideCars.volumes.iscsi.withTargetPortal

```ts
withTargetPortal(targetPortal)
```



## obj spec.sideCars.volumes.iscsi.secretRef



### fn spec.sideCars.volumes.iscsi.secretRef.withName

```ts
withName(name)
```



## obj spec.sideCars.volumes.nfs



### fn spec.sideCars.volumes.nfs.withPath

```ts
withPath(path)
```



### fn spec.sideCars.volumes.nfs.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.sideCars.volumes.nfs.withServer

```ts
withServer(server)
```



## obj spec.sideCars.volumes.persistentVolumeClaim



### fn spec.sideCars.volumes.persistentVolumeClaim.withClaimName

```ts
withClaimName(claimName)
```



### fn spec.sideCars.volumes.persistentVolumeClaim.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.sideCars.volumes.photonPersistentDisk



### fn spec.sideCars.volumes.photonPersistentDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.sideCars.volumes.photonPersistentDisk.withPdID

```ts
withPdID(pdID)
```



## obj spec.sideCars.volumes.portworxVolume



### fn spec.sideCars.volumes.portworxVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.sideCars.volumes.portworxVolume.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.sideCars.volumes.portworxVolume.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.sideCars.volumes.projected



### fn spec.sideCars.volumes.projected.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.sideCars.volumes.projected.withSources

```ts
withSources(sources)
```



### fn spec.sideCars.volumes.projected.withSourcesMixin

```ts
withSourcesMixin(sources)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.volumes.projected.sources



## obj spec.sideCars.volumes.projected.sources.clusterTrustBundle



### fn spec.sideCars.volumes.projected.sources.clusterTrustBundle.withName

```ts
withName(name)
```



### fn spec.sideCars.volumes.projected.sources.clusterTrustBundle.withOptional

```ts
withOptional(optional)
```



### fn spec.sideCars.volumes.projected.sources.clusterTrustBundle.withPath

```ts
withPath(path)
```



### fn spec.sideCars.volumes.projected.sources.clusterTrustBundle.withSignerName

```ts
withSignerName(signerName)
```



## obj spec.sideCars.volumes.projected.sources.clusterTrustBundle.labelSelector



### fn spec.sideCars.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.sideCars.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.sideCars.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions



### fn spec.sideCars.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.sideCars.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.sideCars.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.sideCars.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.volumes.projected.sources.configMap



### fn spec.sideCars.volumes.projected.sources.configMap.withItems

```ts
withItems(items)
```



### fn spec.sideCars.volumes.projected.sources.configMap.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumes.projected.sources.configMap.withName

```ts
withName(name)
```



### fn spec.sideCars.volumes.projected.sources.configMap.withOptional

```ts
withOptional(optional)
```



## obj spec.sideCars.volumes.projected.sources.configMap.items



### fn spec.sideCars.volumes.projected.sources.configMap.items.withKey

```ts
withKey(key)
```



### fn spec.sideCars.volumes.projected.sources.configMap.items.withMode

```ts
withMode(mode)
```



### fn spec.sideCars.volumes.projected.sources.configMap.items.withPath

```ts
withPath(path)
```



## obj spec.sideCars.volumes.projected.sources.downwardAPI



### fn spec.sideCars.volumes.projected.sources.downwardAPI.withItems

```ts
withItems(items)
```



### fn spec.sideCars.volumes.projected.sources.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

## obj spec.sideCars.volumes.projected.sources.downwardAPI.items



### fn spec.sideCars.volumes.projected.sources.downwardAPI.items.withMode

```ts
withMode(mode)
```



### fn spec.sideCars.volumes.projected.sources.downwardAPI.items.withPath

```ts
withPath(path)
```



## obj spec.sideCars.volumes.projected.sources.downwardAPI.items.fieldRef



### fn spec.sideCars.volumes.projected.sources.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.sideCars.volumes.projected.sources.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.sideCars.volumes.projected.sources.downwardAPI.items.resourceFieldRef



### fn spec.sideCars.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.sideCars.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.sideCars.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.sideCars.volumes.projected.sources.secret



### fn spec.sideCars.volumes.projected.sources.secret.withItems

```ts
withItems(items)
```



### fn spec.sideCars.volumes.projected.sources.secret.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumes.projected.sources.secret.withName

```ts
withName(name)
```



### fn spec.sideCars.volumes.projected.sources.secret.withOptional

```ts
withOptional(optional)
```



## obj spec.sideCars.volumes.projected.sources.secret.items



### fn spec.sideCars.volumes.projected.sources.secret.items.withKey

```ts
withKey(key)
```



### fn spec.sideCars.volumes.projected.sources.secret.items.withMode

```ts
withMode(mode)
```



### fn spec.sideCars.volumes.projected.sources.secret.items.withPath

```ts
withPath(path)
```



## obj spec.sideCars.volumes.projected.sources.serviceAccountToken



### fn spec.sideCars.volumes.projected.sources.serviceAccountToken.withAudience

```ts
withAudience(audience)
```



### fn spec.sideCars.volumes.projected.sources.serviceAccountToken.withExpirationSeconds

```ts
withExpirationSeconds(expirationSeconds)
```



### fn spec.sideCars.volumes.projected.sources.serviceAccountToken.withPath

```ts
withPath(path)
```



## obj spec.sideCars.volumes.quobyte



### fn spec.sideCars.volumes.quobyte.withGroup

```ts
withGroup(group)
```



### fn spec.sideCars.volumes.quobyte.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.sideCars.volumes.quobyte.withRegistry

```ts
withRegistry(registry)
```



### fn spec.sideCars.volumes.quobyte.withTenant

```ts
withTenant(tenant)
```



### fn spec.sideCars.volumes.quobyte.withUser

```ts
withUser(user)
```



### fn spec.sideCars.volumes.quobyte.withVolume

```ts
withVolume(volume)
```



## obj spec.sideCars.volumes.rbd



### fn spec.sideCars.volumes.rbd.withFsType

```ts
withFsType(fsType)
```



### fn spec.sideCars.volumes.rbd.withImage

```ts
withImage(image)
```



### fn spec.sideCars.volumes.rbd.withKeyring

```ts
withKeyring(keyring)
```



### fn spec.sideCars.volumes.rbd.withMonitors

```ts
withMonitors(monitors)
```



### fn spec.sideCars.volumes.rbd.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumes.rbd.withPool

```ts
withPool(pool)
```



### fn spec.sideCars.volumes.rbd.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.sideCars.volumes.rbd.withUser

```ts
withUser(user)
```



## obj spec.sideCars.volumes.rbd.secretRef



### fn spec.sideCars.volumes.rbd.secretRef.withName

```ts
withName(name)
```



## obj spec.sideCars.volumes.scaleIO



### fn spec.sideCars.volumes.scaleIO.withFsType

```ts
withFsType(fsType)
```



### fn spec.sideCars.volumes.scaleIO.withGateway

```ts
withGateway(gateway)
```



### fn spec.sideCars.volumes.scaleIO.withProtectionDomain

```ts
withProtectionDomain(protectionDomain)
```



### fn spec.sideCars.volumes.scaleIO.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.sideCars.volumes.scaleIO.withSslEnabled

```ts
withSslEnabled(sslEnabled)
```



### fn spec.sideCars.volumes.scaleIO.withStorageMode

```ts
withStorageMode(storageMode)
```



### fn spec.sideCars.volumes.scaleIO.withStoragePool

```ts
withStoragePool(storagePool)
```



### fn spec.sideCars.volumes.scaleIO.withSystem

```ts
withSystem(system)
```



### fn spec.sideCars.volumes.scaleIO.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.sideCars.volumes.scaleIO.secretRef



### fn spec.sideCars.volumes.scaleIO.secretRef.withName

```ts
withName(name)
```



## obj spec.sideCars.volumes.secret



### fn spec.sideCars.volumes.secret.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.sideCars.volumes.secret.withItems

```ts
withItems(items)
```



### fn spec.sideCars.volumes.secret.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.sideCars.volumes.secret.withOptional

```ts
withOptional(optional)
```



### fn spec.sideCars.volumes.secret.withSecretName

```ts
withSecretName(secretName)
```



## obj spec.sideCars.volumes.secret.items



### fn spec.sideCars.volumes.secret.items.withKey

```ts
withKey(key)
```



### fn spec.sideCars.volumes.secret.items.withMode

```ts
withMode(mode)
```



### fn spec.sideCars.volumes.secret.items.withPath

```ts
withPath(path)
```



## obj spec.sideCars.volumes.storageos



### fn spec.sideCars.volumes.storageos.withFsType

```ts
withFsType(fsType)
```



### fn spec.sideCars.volumes.storageos.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.sideCars.volumes.storageos.withVolumeName

```ts
withVolumeName(volumeName)
```



### fn spec.sideCars.volumes.storageos.withVolumeNamespace

```ts
withVolumeNamespace(volumeNamespace)
```



## obj spec.sideCars.volumes.storageos.secretRef



### fn spec.sideCars.volumes.storageos.secretRef.withName

```ts
withName(name)
```



## obj spec.sideCars.volumes.vsphereVolume



### fn spec.sideCars.volumes.vsphereVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.sideCars.volumes.vsphereVolume.withStoragePolicyID

```ts
withStoragePolicyID(storagePolicyID)
```



### fn spec.sideCars.volumes.vsphereVolume.withStoragePolicyName

```ts
withStoragePolicyName(storagePolicyName)
```



### fn spec.sideCars.volumes.vsphereVolume.withVolumePath

```ts
withVolumePath(volumePath)
```



## obj spec.startup



### fn spec.startup.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.startup.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.startup.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.startup.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.startup.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.startup.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.startup.exec



### fn spec.startup.exec.withCommand

```ts
withCommand(command)
```



### fn spec.startup.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.startup.grpc



### fn spec.startup.grpc.withPort

```ts
withPort(port)
```



### fn spec.startup.grpc.withService

```ts
withService(service)
```



## obj spec.startup.httpGet



### fn spec.startup.httpGet.withHost

```ts
withHost(host)
```



### fn spec.startup.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.startup.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.startup.httpGet.withPath

```ts
withPath(path)
```



### fn spec.startup.httpGet.withPort

```ts
withPort(port)
```



### fn spec.startup.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.startup.httpGet.httpHeaders



### fn spec.startup.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.startup.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.startup.tcpSocket



### fn spec.startup.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.startup.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.users



### fn spec.users.withName

```ts
withName(name)
```

